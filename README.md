# MIT6.824 Lab
## <font color = pink>Set Up</font>
Linux环境配置

> sudo apt install golang-go  
git clone git://g.csail.mit.edu/6.824-golabs-2022 6.824  
cd 6.824   
cd src/main  
go build -race -buildmode=plugin ../mrapps/wc.go  
rm mr-out*   
go run -race mrsequential.go wc.so pg*.txt  
more mr-out-0

根据上述setup，跑通测试程序

## <font color = pink>References</font>
* http://nil.csail.mit.edu/6.824/2022/labs