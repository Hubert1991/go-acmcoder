# go-acmcoder
acmcoder-赛码网站练习题

## 0.参考

- https://exercise.acmcoder.com/online/online_judge_list_all
- go语言版本： **go1.2.1 linux/amd64**（注意版本很老，有些内置函数不能用）
- 输入输出示例：

```go
package main
import "fmt"
import "io"
func main() {
  a:=0
  b:=0
  for {
    _, err := fmt.Scanf("%d%d",&a,&b)
    if err != nil {
        if err == io.EOF {
            break
        }
    } else {
		fmt.Printf("%d\n",a+b)
	}
  }
}
```

## 1.完成的题目

### 基本算法

| No.  | Title                                                        | Tag（自定义） | 难度 | 完成情况 |
| ---- | ------------------------------------------------------------ | ------------- | ---- | -------- |
|      | 第1期                                                        |               |      |          |
| 0001 | [股神](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=1664&konwledgeId=134) | 计算          | 3    | 完成     |
| 0002 | [翻转数组](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=1656&konwledgeId=134) | 数组          | 3    | 完成     |
| 0003 | [约德尔测试](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=1677&konwledgeId=134) | 字符串        | 2    | 完成     |
| 0004 | [路灯](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=1500&konwledgeId=134) | 数组          | 4    | 完成     |
| 0005 | [计算器的新功能](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=1684&konwledgeId=134) | 数学          | 3    |          |
| 0006 | [公交车乘客](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=1659&konwledgeId=134) | 数组          | 2    | 完成     |
| 0007 | [分苹果](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=1654&konwledgeId=134) | 数学          | 3    | 完成     |
| 0008 | [马路上的路灯](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=1652&konwledgeId=134) | 数组          | 3    | 完成     |
| 0009 | [日期倒计时](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=1649&konwledgeId=134) | 时间          | 3    | 完成     |
| 0010 | [比大小](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=1660&konwledgeId=134) |               | 3    |          |
| 0011 | [约会](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=1530&konwledgeId=134) | 数学          | 1    | 完成     |
| 0012 | [研究生考试](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=3007&konwledgeId=134) | 数学          | 2    | 完成     |
| 0013 | [行编辑器](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=3008&konwledgeId=134) | 栈            | 2    | 完成     |
| 0014 | [接金币](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=3009&konwledgeId=134) | 动态规划      | 2    | 完成     |
| 0015 | [文艺青年爱文学](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=3010&konwledgeId=134) | 动态规划      | 2    | 完成     |
| 0016 | [下起楼来我最快](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=3011&konwledgeId=134) | 数学          | 2    | 完成     |
| 0017 | [回文串](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=3013&konwledgeId=134) | 字符串        | 2    | 完成     |
| 0018 | [小赛的升级之路](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=3023&konwledgeId=134) | 数学          | 4    | 完成     |
| 0019 | [装载乘客](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=3017&konwledgeId=134) | 数组          | 2    | 完成     |
| 0020 | [搬圆桌](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=3012&konwledgeId=134) | 几何          | 2    | 完成     |
| 0021 | [喷水装置](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=1651&konwledgeId=134) | 几何          | 3    | 完成     |
| 0022 | [投篮游戏](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=3016&konwledgeId=134) | 数组          | 2    | 完成     |
| 0023 | [三分线](https://exercise.acmcoder.com/online/online_judge_ques?ques_id=1531&konwledgeId=134) |               | 2    |          |

