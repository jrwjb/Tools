一、 运行环境python3 : 安装依赖 pip install -r requirements.txt (若已安装可忽略)
二、 项目路径下需有project_information文件（同网页版报告使用同一个信息表），运行脚本前自行修改该文件里对应的内容，生成报告结果保存在项目路径下。
三、 运行脚本 python autoReport.py -i 项目路径 -t 项目类型
参数：
	-i 项目路径 （必须参数）
	-t 项目类型 （必须参数）

项目类型参数(s为16S)

注：可执行 python autoReport.py --help查看帮助

若 pip install -r requirements.txt 安装失败，可单独安装各模块，例如：
安装 win32com.client 命令
python -m pip install pypiwin32
