训练+测试结果prf：
1.修改config.yml文件（调参）（不需要指定训练和验证文件路径）
2.信息中心上,激活环境tensorflow 执行python train.py data/train/train0 data/test/test0



得到测试结果文件：
1.修改config.yml文件path_test（测试文件路径），model_restore_path（训练好的模型的路径）两个参数
2.信息中心上,激活环境tensorflow 执行python test.py
