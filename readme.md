## Project Description

A home renew project

mail to example
```html
<form action="mailto:2aixdgxu@gmail.com" method="post" enctype="text/plain" accept-charset="utf-8">
<!-- 寄件者姓名    -->
<input id="nameText" type="text" name="Name" value="" size="60" placeholder="姓名(name)" required="">  <!-- required 必填欄位 &#65292;placeholder 預設內容--> 

<!-- 寄件者email -->
<input id="emailText" type="email" name="Email" value="" size="60" placeholder="Email" required="">

<!-- 寄件者電話 -->
<input id="telText" type="tel" name="Phone" value="" size="60" aria-invalid="false" placeholder="電話(phone)" required="">

<!-- 郵件主旨 -->
<input id="subText" type="text" name="Subject" value="" size="60" aria-invalid="false" placeholder="主旨(subject)" required="">

<!-- 郵件內容 -->
<textarea id="bodyText" name="your-message" cols="40" rows="10" aria-required="true" aria-invalid="false" placeholder="你的訊息(Your Message)" required=""></textarea>
<div>
<input type="submit" value="Send">
<input type="reset" value="Reset">
</div>
</form>
```
