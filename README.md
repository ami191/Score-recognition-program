music_recognizer/
│
├── music_recognition.py      # 主程序
├── start.py                  # 启动脚本
├── train_model.py           # 模型训练
├── batch_process.py         # 批量处理
├── api_server.py            # API服务
│
├── config/                  # 配置文件
│   ├── settings.json
│   ├── training.json
│   └── models.json
│
├── data/                    # 数据目录
│   ├── audio/              # 音频文件
│   ├── midi/               # MIDI文件
│   ├── training/           # 训练数据
│   └── dataset.pkl         # 序列化数据集
│
├── models/                  # 模型文件
│   ├── best_model.h5
│   ├── final_model.h5
│   └── pretrained/
│
├── output/                  # 输出目录
│   ├── batch/              # 批量处理结果
│   └── (各种输出文件)
│
├── src/                    # 源代码
│   ├── analyzer.py         # 音频分析器
│   ├── detector.py         # 音符检测器
│   ├── generator.py        # 乐谱生成器
│   ├── gui.py             # GUI界面
│   └── utils.py           # 工具函数
│
├── tests/                  # 测试文件
│   ├── test_audio.wav
│   └── test_recognition.py
│
├── docs/                   # 文档
│   ├── README.md
│   ├── API.md
│   └── user_guide.md
│
├── requirements.txt        # 依赖列表
└── README.md              # 项目说明
