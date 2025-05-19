# 鱼你同行项目

这是一个使用Vue前端和Django后端的全栈应用项目。

## 项目结构

```
fish_with_you/
├── backend/             # Django后端项目
│   ├── fish_backend/    # Django项目配置
│   └── manage.py        # Django管理脚本
└── frontend/            # Vue前端项目
    └── fish_frontend/   # Vue项目文件
```

## 后端 (Django)

### 安装依赖

```bash
cd backend
pip install -r requirements.txt  # 将来会创建此文件
```

### 运行开发服务器

```bash
cd backend
python manage.py runserver
```

## 前端 (Vue)

### 安装依赖

```bash
cd frontend/fish_frontend
npm install
```

### 运行开发服务器

```bash
cd frontend/fish_frontend
npm run serve
```

## 开发说明

- 后端API将运行在 http://localhost:8000/
- 前端开发服务器将运行在 http://localhost:8080/
