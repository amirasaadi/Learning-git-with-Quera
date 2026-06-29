دیدن تاریخچه کامیت‌های گذشته

```bash
git log <BRANCH>
```
دیدن همه کامیت‌های شاخه فعلی

```bash
git log -n 5
```
دیدن ۵ کامیت آخر

```bash
git log --author="X"
```
دیدن کامیت‌هایی که شخص خاصی زده


```bash
git log --before="2021-01-02"
git log --after="2 hours ago"
git log --before="yesterday"
git log --after="2am"
```
دیدن کامیت‌هایی که قبل یا بعد از تاریخ فلان زده شدن

```bash
git log -- main.py
```
کامیت‌هایی که مربوط به فایل main.py هستند

```bash
git log -S"print("hello world")"
```
کامیت‌هایی که دستور print هلو ورد دارند

```bash
git log --grep="very important"
```
کامیتی که تو پیامش عبارت very important داره

```bash
git log --oneline
```

```bash
git log --pretty=oneline 
```
دیدن هر کامیت در یک خط


```bash
git log --graph
```
دیدن گراف لاگ‌ها