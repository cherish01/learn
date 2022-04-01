## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/cherish01/learn/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### 排序
    （1）插入排序：直接插入排序、二分法插入排序、希尔排序

    （2）选择排序：直接选择排序、堆排序

    （3）交换排序：冒泡排序、快速排序

    （4）归并排序

    （5）基数排序

![image](https://user-images.githubusercontent.com/24765262/160609856-ab3b89e8-9630-443d-b735-d37d79fe60a2.png)

```markdown
# [::-1]:用法
import numpy as np
a=np.random.rand(5)
print(a)
[ 0.64061262 0.8451399  0.965673  0.89256687 0.48518743]
print(a[-1]) ###取最后一个元素
[0.48518743]
print(a[:-1]) ### 除了最后一个取全部
[ 0.64061262 0.8451399  0.965673  0.89256687]
print(a[::-1]) ### 取从后向前（相反）的元素
[ 0.48518743 0.89256687 0.965673  0.8451399  0.64061262]
print(a[2::-1]) ### 取从下标为2的元素翻转读取
[ 0.965673 0.8451399  0.64061262]

**Bold** and _Italic_ and `Code` text
[Link](url) and ![Image](src)
```

### PPO标准教学
https://github.com/louisnino/RLcode/blob/10296e8536e5f661a05be2d3995363e8cf36194c/tutorial_PPO.py

### 推导
https://blog.csdn.net/qq_37266917/article/details/109855244
### PPO 调度改进 ？


