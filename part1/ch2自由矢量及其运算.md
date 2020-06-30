# 自由矢量及其运算
A given oriented line segment defines a free vector.
## 1 矢量和
$$
\underline{c}=\underline{a}+\underline{b} \Leftrightarrow \underline{c}=\underline{b}+\underline{a}
$$
## 2 矢量乘以标量
$$
\underline{b}=\alpha\underline{a}
$$
## 3 矢量的模
$$
||\underline{a}||=a
$$
$$
||\alpha\underline{a}||=|\alpha|||\underline{a}||
$$
$$
||\underline{a}+\underline{b}||\leq ||\underline{a}||+||\underline{b}||
$$
单位矢量
$$
\bar{a}=\frac{\underline{a}}{||\underline{a}||},\quad ||\bar{a}||=1
$$
## 4 矢量夹角
$$
\varPhi=(\underline{a},\underline{b})=(\underline{b},\underline{a}),\quad 0\leq\varPhi\leq\pi,\quad \sin\varPhi\geq0
$$
## 5 标量积
$$
\sigma=\underline{a}^{\rm{T}}\underline{b}=||\underline{a}||||\underline{b}||\cos(\underline{a},\underline{b})
$$
满足交换律
$$
\underline{a}^{\rm{T}}\underline{b}=\underline{b}^{\rm{T}}\underline{a}
$$
满足分配律
$$
(\underline{a}+\underline{b})^{\rm{T}}\underline{c}=\underline{a}^{\rm{T}}\underline{c}+\underline{b}^{\rm{T}}\underline{c} 
$$
$$
\underline{a}^{\rm{T}}(\underline{b}+\underline{c})=\underline{a}^{\rm{T}}\underline{b}+\underline{a}^{\rm{T}}\underline{c} 
$$
其它性质
$$
\underline{a}^{\rm{T}}\underline{a}=||\underline{a}||^2=a^2
$$
$$\underline{a}^{\rm{T}}\underline{b}=0\Rightarrow\left\{ \begin{matrix}
\underline{a}=\underline{0}\\ or \quad \underline{b}=\underline{0}\\ or\quad \underline{a}\perp\underline{b} 
\end{matrix}\right.$$
投影：
$$
\rho=\underline{a}^{\rm{T}}\bar{n}=||\underline{a}||\cos(\underline{a},\bar{n})
$$
## 6 正交基
$$
\bar{i}^{\mathcal{L}}_{1}=\left(\begin{matrix}
    1\\0\\0
\end{matrix}\right),\quad \bar{i}^{\mathcal{L}}_{2}=\left(\begin{matrix}
    0\\1\\0
\end{matrix}\right),\quad \bar{i}^{\mathcal{L}}_{3}=\left(\begin{matrix}
    0\\0\\1
\end{matrix}\right)
$$
同时，有
$$
\underline{a}^{\rm{T}}\underline{b}=a_{1}b_{1}+a_{2}b_{2}+a_{3}b_{3}=(a_{1}\quad a_{2} \quad a_{3})\left(\begin{matrix}
b_{1} \\b_{2}\\b_{3}
\end{matrix}\right)
$$
## 7 矢量积(叉积)
$$
\underline{c}=\tilde{a}\underline{b}=||\underline{a}||||\underline{b}||\sin(\underline{a},\underline{b})\bar{n}
$$
叉积有以下性质
$$
\tilde{a}\underline{b}=-\tilde{b}\underline{a}
$$
分配律
$$
(\tilde{a}+\tilde{b})\underline{c}=\tilde{a}\underline{c}+\tilde{b}\underline{c}
$$
$$
\tilde{a}(\underline{b}+\underline{c})=\tilde{a}\underline{b}+\tilde{a}\underline{c}
$$
$$
\tilde{a}\underline{b}=0 \Rightarrow \underline{a}=\underline{0}或者 \underline{b}=\underline{0} 或者 \underline{a}//\underline{b}
$$
$$
\tilde{a}^{\mathcal{L}}=\left(\begin{matrix}
0\quad -a_{3} \quad a_{2}\\a_{3}\quad 0\quad -a_{1}\\-a_{2}\quad a_{1}\quad 0 
\end{matrix} \right)
$$
称作矢量$\underline{a}$在坐标系$\mathcal{L}$下的反对称张量。
## 8 张量积(二阶张量)
$$
\underline{\underline{T}}=\underline{a}\underline{b}^{\rm{T}}
$$
性质
$$
\underline{\underline{T}}\underline{c}=(\underline{b}^{\rm{T} }\underline{c})\underline{a}
$$
$$
\underline{\underline{T}}^{\mathcal{L}}=\left(\begin{matrix}
a_{1}b_{1}\quad a_{1}b_{2} \quad a_{1}b_{3}\\a_{2}b_{1}\quad a_{2}b_{2}\quad a_{2}b_{3}\\a_{3}b_{1}\quad a_{3}b_{2}\quad a_{3}b_{3}
\end{matrix}\right)
$$
## 9 混合积
$$
\underline{c}^{\rm{T}}\tilde{a}\underline{b}=det\left(\begin{matrix}
a_{1} \quad a_{2} \quad a_{3}\\b_{1} \quad b_{2} \quad b_{3}\\c_{1} \quad c_{2} \quad c_{3}
\end{matrix}\right)
$$
性质：顺序不变则符号不变
$$
\underline{a}^{\rm{T}}\tilde{b}\underline{c}=\underline{b}^{\rm{T}}\tilde{c}\underline{a}=\underline{c}^{\rm{T}}\tilde{a}\underline{b}
$$
## 10 张量性质
$$
\widetilde{\tilde{a}\underline{b}}=\tilde{a}\tilde{b}-\tilde{b}\tilde{a}
$$
$$
\tilde{a}\tilde{b}-\tilde{b}\tilde{a}=\underline{b}\underline{a}^{\rm{T}}-\underline{b}\underline{a}^{\rm{T}}
$$
$$
\tilde{a}\tilde{b}=\underline{b}\underline{a}^{\rm{T}}-(\underline{a}^{\rm{T}}\underline{b})\underline{\underline{I}}
$$
$$
\tilde{a}\tilde{b}-\underline{a}\underline{b}^{\rm{T}}=\widetilde{\tilde{a}b}-(\underline{a}^{\rm{T}}\underline{b})\underline{\underline{I}}
$$
$$
\widetilde{\tilde{a}b}\underline{c}=(\underline{a}^{\rm{T}}\underline{c})\underline{b}-(\underline{b}^{\rm{T}}\underline{c})\underline{a}
$$
$$
\tilde{a}\tilde{b}\underline{c}=(\underline{a}^{\rm{T}}\underline{c})\underline{b}-(\underline{a}^{\rm{T}}\underline{b})\underline{c}
$$
$$
\underline{a}\underline{b}^{\rm{T}}\underline{c}=(\underline{b}^{\rm{T}}\underline{c})\underline{a}
$$
$$
\underline{a}^{\rm{T}}\tilde{b}\underline{c}=\underline{b}^{\rm{T}}\tilde{c}\underline{a}=\underline{c}^{\rm{T}}\tilde{a}\underline{b}
$$