# FormatEditText
身份证，银行卡，手机号自动格式化的EditText
```xml
<declare-styleable name="clear_edit_attrs">
    <attr name="input_type" format="enum">
        <enum name="normal" value="0" />
        <enum name="phone" value="1"/>
        <enum name="card" value="2"/>
        <enum name="IDcard" value="3"/>
    </attr>
</declare-styleable>
```
默认为0，不进行格式化
需要格式化时，请使用自定义属性 如：
```xml
app：input_type="card"
```
