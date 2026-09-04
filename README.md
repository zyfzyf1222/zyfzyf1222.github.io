# zyfzyf1222.github.io — Academic Homepage

这是一个可直接部署到 GitHub Pages 的个人学术主页项目。

## 文件结构

```text
.
├── index.html
├── styles.css
├── script.js
├── assets/
│   └── profile-placeholder.svg
└── certificates/
    └── README.md
```

## 1. 放个人照片

把你的个人照片放到：

```text
assets/profile.jpg
```

然后在 `index.html` 中把：

```html
<img src="assets/profile-placeholder.svg" ...>
```

改为：

```html
<img src="assets/profile.jpg" ...>
```

建议照片比例约为 4:5，正式证件照、半身照或学术风格照片都可以。

## 2. 放证书 PDF

把真实 PDF 放进 `certificates/` 文件夹，并使用下列文件名：

- merit_student.pdf
- outstanding_student_leader.pdf
- outstanding_youth_leader.pdf
- university_scholarship.pdf
- jiangsu_senhe_scholarship.pdf
- hollysys_first_scholarship.pdf
- cet.pdf
- graduate_recommendation.pdf
- smart_car_national_first.pdf
- smart_car_provincial.pdf
- cimc_19.pdf
- datacom_cup_national_second.pdf
- anhui_innovation_bronze_2025.pdf

## 3. 上传 GitHub

把项目内所有文件上传到：

`zyfzyf1222.github.io`

仓库根目录。

然后：

`Settings -> Pages -> Deploy from a branch -> main -> /(root)`

最终网址：

`https://zyfzyf1222.github.io`

## 4. 可继续修改

- `index.html`：个人信息、项目、奖项
- `styles.css`：颜色、布局、字体
- `script.js`：移动端菜单
