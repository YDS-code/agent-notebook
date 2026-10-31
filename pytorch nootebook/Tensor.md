1.定义：pytorch中的多维数组
2.使用：
（1）：一维数组 x = torch.tensor([1, 2, 3]) 
（2）：二维数组 x = torch.tensor([
				    [1, 2, 3],
				    [4, 5, 6]
							])
			   x.shape->[2,3] 2行3列
 （3）：三维数组 x = torch.randn(2, 5, 8)
			   x.shape->torch.Size([2, 5, 8]) 表示2个句子，每个句子5个词元，每个词元有8维向量
