# ``<label>``标签

``<label>``标签为input元素定义标注(标签)

``<label>``标签用于绑定一个表单元素,当点击``<label>``标签内的文本时,浏览器就会自动将光标转到或者选择对应的表单元素来上,用来增加用户体验

**语法:**
````html
<label for="sex">男</label>
<input  type="radio" name="sex" id="sex" />
````

**核心:**``<label>``标签的for属性应当与相关元素的id属性相同