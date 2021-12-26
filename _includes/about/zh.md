# Eilmer 可以用来...

Eilmer 是用来对二维或三维瞬态可压缩流动进行数值仿真的代码库。
您可以通过给定计算域、初始流动状态、边界条件




# 谁打造了Eilmer？ 为什么呢？
最主要的开发者是来自于澳大利亚昆士兰大学的 Dr. Peter Jacobs 和 Dr. Rowan Gollan.
近年来亦有很多开发者做出了出色的贡献。
完整的贡献者名单请[点击](http://cfcfd.mechmining.uq.edu.au/eilmer/contributors/).

Eilmer 是从辅助涉及激波风洞和扩压管开始做为一个仿真工具来使用的。
同时Eilmer也用来仿真在激波风洞和扩压管中的实验项目。

最近，Eilmer拓展到了高超声速、涡轮机械及微尺度燃烧器的设计及仿真领域。

Eilmer的[英文网站](https://gdtk.uqcloud.net/docs/eilmer/about/)上可以查看更多有用的信息。

为方便用户使用，我们隆重推出了[Eilmer用户指南](https://github.com/eilmerinchina/eilmerinchina.github.io/blob/master/_includes/about/ChineseEilmer_2021_10_12_update.pdf)的中文版

# Eilmer的特别之处
* 二维/三维可压缩流动仿真
* 包括理想气体、热力学完美气体、相平衡、多温在内的多种热力学模型
* 有限速率化学反应
* 无黏流、层流、湍流 (k-omega)流动
* 二维的固体控制域及耦合换热
* 可由用户控制的移动网格
* 二维结构激波自适应方法
* 适用于转动机械的质密气体热力学模型及旋转参考系方法
* 瞬态、时间准确，使用显示欧拉方法，Transient, time-accurate, using explicit Euler, predictor-corrector and Runge-Kutta updates.
* 使用Newton-Krylov方法的稳态求解器
* 使用共享内存的并行计算
* Multiple block, structure and unstructured grids.
* Native grid generation and import capability.
* Unstructured-mesh partitioning via Metis.


# 如何做贡献？


# 如何引用Eilmer？

我们希望通过使用Eilmer，您可以通过创造一些高品质的仿真工作，来辅助您的科研或工作。
当您准备汇报您的Eilmer仿真时，我们希望您通够通过引用Eilmer的文章来致谢。
具体的引用方式为：

Jacobs P.A. and Gollan R.J. (2016)
<cite>Implementation of a Compressible-Flow Simulation Code in the D Programming Language.</cite>
Advances of Computational Mechanics in Australia; 846:54-60
(DOI: 10.4028/www.scientific.net/AMM.846.54)

Gollan R.J. and Jacobs P.A. (2013)
<cite>About the formulation, verification and validation of the hypersonic flow solver Eilmer.</cite>
International Journal for Numerical Methods in Fluids; 73:19-57
(DOI: 10.1002/fld.3790)


# 证书
For the source code, we use the GNU General Public License 3. Please see the file <code>gpl.txt</code> in the source tree.

For the documentation, such as this website, we use the Creative Commons Attribution-ShareAlike 4.0 International License.



