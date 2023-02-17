# -
O.
模型训练：终端输入：python3 tools/train.py --config_file "config/icdar2015_resnet18_FPN_DBhead_polyLR.yaml"  
模型测试：终端输入：python3 tools/eval.py --model_path './output/DBNet_resnet18_FPN_DBHead/checkpoint/model_best.pth'
结果预测：终端输入：python3 tools/predict.py --model_path './output/DBNet_resnet18_FPN_DBHead/checkpoint/model_best.pth'
