GLKVector3参考
PDFCompanion文件
* 		
* 		
下一个
GLKVector3参考
骨架	GLKit / GLKMath.h
宣称	GLKMathTypes.h 
GLKVector3.h
概观
该GLKVector3类型定义了一个组件3浮点向量以及通常用于操纵向量的许多数学运算。图形编程广泛使用向量来表示位置，法线，颜色和其他数据结构。
操作GLKVector3结构的函数将输入视为不可变的，而返回一个代表操作结果的新向量。
功能按任务
创建向量
* 		GLKVector3Make
* 		GLKVector3MakeWithArray
检索关于矢量的信息
* 		GLKVector3Length
* 		GLKVector3Distance
向量执行的数学操作
* 		GLKVector3Negate
* 		GLKVector3Normalize
* 		GLKVector3AddScalar
* 		GLKVector3SubtractScalar
* 		GLKVector3MultiplyScalar
* 		GLKVector3DivideScalar
* 		GLKVector3Add
* 		GLKVector3Subtract
* 		GLKVector3Multiply
* 		GLKVector3Divide
* 		GLKVector3DotProduct
* 		GLKVector3CrossProduct
* 		GLKVector3Lerp
* 		GLKVector3Project
* 		GLKVector3Maximum
* 		GLKVector3Minimum
比较操作
* 		GLKVector3AllEqualToScalar
* 		GLKVector3AllEqualToVector3
* 		GLKVector3AllGreaterThanOrEqualToScalar
* 		GLKVector3AllGreaterThanOrEqualToVector3
* 		GLKVector3AllGreaterThanScalar
* 		GLKVector3AllGreaterThanVector3
功能
GLKVector3Add
返回两个向量的和。
GLKVector3 GLKVector3Add（GLKVector3 vectorLeft，GLKVector3 vectorRight）;
参数
vectorLeft
第一个矢量。
vectorRight
第二个矢量。
回报值
一个新向量，其分量各自表示在两个源向量的相同位置中发现的两个分量之和。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3AddScalar
返回通过向向量的每个组件添加标量值创建的新向量。
GLKVector3 GLKVector3AddScalar（GLKVector3 vector，float value）;
参数
向量
一个矢量。
值
标量值。
回报值
一个新的矢量。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3AllEqualToScalar
返回一个布尔值，指示源向量的所有组件是否等于标量值。
bool GLKVector3AllEqualToScalar（GLKVector3 vector，float value）;
参数
向量
一个矢量。
值
标量
回报值
YES如果所有矢量的分量都等于值，NO否则。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3AllEqualToVector3
返回一个布尔值，指示第一个向量的每个分量是否等于第二个向量的相应分量。
bool GLKVector3AllEqualToVector3（GLKVector3 vectorLeft，GLKVector3 vectorRight）;
参数
vectorLeft
第一个矢量。
vectorRight
第二个矢量。
回报值
YES如果所有的矢量组件相同，NO否则。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3AllGreaterThanOrEqualToScalar
返回一个布尔值，指示源向量的所有组件是否大于或等于标量值。
bool GLKVector3AllGreaterThanOrEqualToScalar（GLKVector3 vector，float value）;
参数
向量
一个矢量。
值
标量
回报值
YES如果所有矢量的分量都大于或等于标量值，NO否则。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3AllGreaterThanOrEqualToVector3
返回一个布尔值，指示第一个向量的每个分量是否大于或等于第二个向量的相应分量。
bool GLKVector3AllGreaterThanOrEqualToVector3（GLKVector3 vectorLeft，GLKVector3 vectorRight）;
参数
vectorLeft
第一个矢量。
vectorRight
第二个矢量。
回报值
YES如果第一向量中的每个分量大于或等于第二向量的相应分量，NO否则。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3AllGreaterThanScalar
返回一个布尔值，指示源向量的所有组件是否大于标量值。
bool GLKVector3AllGreaterThanScalar（GLKVector3 vector，float value）;
参数
向量
一个矢量。
值
标量
回报值
YES如果所有矢量的分量都大于标量值，NO否则。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3AllGreaterThanVector3
返回一个布尔值，指示第一个向量的每个分量是否大于第二个向量的相应分量。
bool GLKVector3AllGreaterThanVector3（GLKVector3 vectorLeft，GLKVector3 vectorRight）;
参数
vectorLeft
第一个矢量。
vectorRight
第二个矢量。
回报值
YES如果第一矢量中的每个分量大于第二矢量的相应分量，NO否则。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3CrossProduct
返回两个向量的交叉乘积。
GLKVector3 GLKVector3CrossProduct（GLKVector3 vectorLeft，GLKVector3 vectorRight）;
参数
vectorLeft
第一个矢量。
vectorRight
第二个矢量。
回报值
一个新的矢量。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3Distance
返回两点之间的距离。
float GLKVector3Distance（GLKVector3 vectorStart，GLKVector3 vectorEnd）;
参数
vectorStart
提供起点坐标的向量。
vectorEnd
提供终点坐标的向量。
回报值
两点之间的距离。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3Divide
返回通过将一个向量除以另一个矢量创建的新向量。
GLKVector3 GLKVector3Divide（GLKVector3 vectorLeft，GLKVector3 vectorRight）;
参数
vectorLeft
第一个矢量。
vectorRight
股息
回报值
通过将在第一矢量的相同位置中找到的分量除以在第二矢量的相同位置中找到的分量，分别计算其分量的新向量。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3DivideScalar
返回通过将向量的每个分量除以标量值创建的新向量。
GLKVector3 GLKVector3DivideScalar（GLKVector3 vector，float value）;
参数
向量
一个矢量。
值
标量值。
回报值
一个新的矢量。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3DotProduct
返回两个向量的点积。
float GLKVector3DotProduct（GLKVector3 vectorLeft，GLKVector3 vectorRight）;
参数
vectorLeft
第一个矢量。
vectorRight
第二个矢量。
回报值
两个向量的点积。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3Length
返回向量的长度。
float GLKVector3Length（GLKVector3 vector）;
参数
向量
一个矢量。
回报值
矢量的长度。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3Lerp
返回通过两个向量之间的线性解释创建的新向量。
GLKVector3 GLKVector3Lerp（GLKVector3 vectorStart，GLKVector3 vectorEnd，float t）;
参数
vectorStart
起始矢量。
vectorEnd
结束向量。
Ť
内插常数。
回报值
一个新的矢量。
讨论
的值吨通常应该之间0.0和1.0。的值0.0返回初始向量和的值1.0返回结束矢量。t的任何其他值导致两点之间的线性插值。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3Make
返回从各个组件值创建的新的三分量向量。
GLKVector3 GLKVector3Make（float x，float y，float z）;
参数
X
第一个组件。
ÿ
第二个组件。
ž
第三部分。
回报值
初始化矢量。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3MakeWithArray
返回从组件数组创建的新的三分量向量。
GLKVector3 GLKVector3MakeWithArray（float values [3]）;
参数
值
数组包含组件值。
回报值
数组。
讨论
初始化矢量。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3Maximum
返回一个新向量，其中每个位置的分量值是源向量中相同位置处的最大分量值。
GLKVector3 GLKVector3Maximum（GLKVector3 vectorLeft，GLKVector3 vectorRight）;
参数
vectorLeft
第一个矢量。
vectorRight
第二个矢量。
回报值
一个新的矢量。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3Minimum
返回一个新向量，其中每个位置的分量值是源向量中相同位置处的最小分量值。
GLKVector3 GLKVector3Minimum（GLKVector3 vectorLeft，GLKVector3 vectorRight）;
参数
vectorLeft
第一个矢量。
vectorRight
第二个矢量。
回报值
一个新的矢量。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3Multiply
返回两个向量的乘积。
GLKVector3 GLKVector3Multiply（GLKVector3 vectorLeft，GLKVector3 vectorRight）;
参数
vectorLeft
第一个矢量。
vectorRight
第二个矢量。
回报值
一个新向量，其分量各自表示在两个源向量的相同位置中发现的分量的乘积。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3MultiplyScalar
返回通过将向量的每个分量乘以标量值创建的新向量。
GLKVector3 GLKVector3MultiplyScalar（GLKVector3 vector，float value）;
参数
向量
一个矢量。
值
标量值。
回报值
一个新的矢量。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3Negate
返回通过否定另一个向量的组件值创建的新向量。
GLKVector3 GLKVector3Negate（GLKVector3 vector）;
参数
向量
一个矢量。
回报值
一个新的矢量。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3Normalize
返回通过将输入向量归一化为一段长度创建的新向量1.0。
GLKVector3 GLKVector3Normalize（GLKVector3 vector）;
参数
向量
一个矢量。
回报值
一个新的矢量。
讨论
所得到的向量指向与输入向量相同的方向，但具有长度1.0。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3Project
返回通过将向量投影到另一个向量上创建的新向量。
GLKVector3 GLKVector3Project（GLKVector3 vectorToProject，GLKVector3 projectionVector）;
参数
vectorToProject
正在投影的矢量。
projectionVector
投影向量。
回报值
一个新的矢量。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3Subtract
返回两个向量之间的差异。
GLKVector3 GLKVector3Subtract（GLKVector3 vectorLeft，GLKVector3 vectorRight）;
参数
vectorLeft
起始矢量。
vectorRight
向量减去。
回报值
一个新向量，其分量各自表示在两个源向量的相同位置中发现的分量之间的差异。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
GLKVector3SubtractScalar
返回通过从矢量的每个分量中减去标量值创建的新向量。
GLKVector3 GLKVector3SubtractScalar（GLKVector3 vector，float value）;
参数
向量
一个矢量。
值
标量值。
回报值
一个新的矢量。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKVector3.h
数据类型
GLKVector3
3分量矢量的表示。
union _GLKVector3 {struct {float x，y，z; }; struct {float r，g，b; }; struct {float s，t，p; }; float v [3];}; typedef union _GLKVector3 GLKVector3;
字段
x
矢量中的第一个组件。通常在矢量指的是位置或正常时使用。
y
向量中的第二个组件。通常在矢量指的是位置或正常时使用。
z
向量中的第三个组件。通常在矢量指的是位置或正常时使用。
r
矢量中的第一个组件。通常在矢量指的是颜色值时使用。
g
向量中的第二个组件。通常在矢量指的是颜色值时使用。
b
向量中的第三个组件。通常在矢量指的是颜色值时使用。
s
矢量中的第一个组件。通常在矢量指纹理坐标时使用。
t
向量中的第二个组件。通常在矢量指纹理坐标时使用。
p
向量中的第三个组件。通常在矢量指纹理坐标时使用。
v
向量的元素表示为数组。
可用性
* 		适用于iOS 5.0及更高版本。
声明在
GLKMathTypes.h
