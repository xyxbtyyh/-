## 作业内容
制作一个“个人简介”页面，包含个人姓名、简介、照片、兴趣爱好和联系方式。
## 使用到的标签
<!DOCTYPE html>
<html>：根元素，设置语言为 zh-CN
<head>：头部，包含 meta 和 title
<h1>、<h2>：标题
<p>：段落
<strong>：加粗关键词
<em>：强调语气
<hr>：分割线
<img>：图片，设置了 alt 属性
<br>`：换行
<a>`：超链接，其中一个使用了 target="_blank"
<!-- -->注释

## 遇到的困难及解决方法
困难：Git 推送超时。解决：使用手机热点或加速工具，重新推送。
# 第二次作业：用户注册页面

## 作业内容
制作一个“用户注册”页面，综合运用列表、表格、表单三大模块，包含了语义化标签、表单控件属性、label关联、JavaScript数据收集等功能。

## 使用到的标签与属性
- 语义化标签：`<header>`, `<main>`, `<footer>`, `<h1>`, `<h2>`, `<h3>`
- 列表标签：`<ul>`, `<ol>`, `<dl>`, `<dt>`, `<dd>`, `<li>`
- 表格标签：`<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`, `colspan` 合并单元格
- 表单标签：`<form>`, `<input>` (text, password, radio, date, email, tel, checkbox, file), `<select>`, `<option>`, `<textarea>`, `<button>`
- 表单属性：`name`, `value`, `placeholder`, `checked`, `selected`, `required`, `pattern`, `accept`, `multiple`, `rows`, `cols`
- 关联标签：`<label>` 包裹式与 `for`+`id` 式

## 遇到的困难及解决方法
- 困难：在表单中使用多个复选框（checkbox）时，数据传输格式容易出错。
- 解决：在JavaScript中使用 `FormData` 配合自定义逻辑处理同名字段，将其转换为数组格式，确保控制台打印数据完整。
- 困难：Git推送受网络限制。
- 解决：继续沿用上次成功的方法，若超时则切换手机热点或开启加速工具。