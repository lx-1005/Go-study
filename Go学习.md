
单测：

执行以下命令，会运行当前目录下的所有_test.go文件
    运行单测文件：go test -v
    运行基准测试：go test -bench=.
    运行指定测试用例（单测函数TestArea下的子测试Rec）：go test -run TestArea/Rec
    查看覆盖率：go test -cover
    