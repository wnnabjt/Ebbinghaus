如要添加任务，只需在data_in.txt文件的最后一行添加 (日期(char*) 任务代号(int)) 格式的数据，最后换行保存即可。
运行Ebbinghaus程序，即可得到当天复习任务，以及日程表中的所有复习任务。

"""
该版本的程序不支持跨年数据的处理，譬如12/20 01，则不会显示正确结果，有间隔15天复习不会显示。
该程序仅采用艾浩宾斯记忆法中的部分内容，即仅采用背诵过后1, 2, 4, 7, 15天复习这些内容，如需更多内容(天数)请适当修改intervel数组和数组的遍历相关内容即可。
data_in中现有的数据为测试数据，使用时直接全部删除，务必按照格式添加自己的内容即可。
"""