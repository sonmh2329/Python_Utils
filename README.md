# Python_Utils

## 1. Sử dụng Pymon để listening files changes

Đây là module giúp auto restart project tương tự như `nodemon` của nodejs

```shell
pip install py-mon watchdog
```

Để chạy:

```shell
pymon -all <dir>
```

Với `-all` để listen tất cả file `.py` change và `<dir>` là đường dẫn file chạy chính của project, thường là path đến `app.py`.

Đọc thêm [tại đây]()

## 2. Progress bar với tqdm

Link tham khảo [https://towardsdatascience.com/training-models-with-a-progress-a-bar-2b664de3e13e](https://towardsdatascience.com/training-models-with-a-progress-a-bar-2b664de3e13e)