---
title: Diametric: Recreating the Demo - Panel Title & SubTitle
description: Your Guide to Recreating Elements of the Diametric Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/diametric:Diametric

---

Panel Title & SubTitle
-----
![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting        |  
| :--------- | :------------- |  
| Title      | `FP MainTop A` |  
| Show Title | Hide           |  
| Position   | content-top-b  |  
| Status     | Published      |  
| Access     | Public         |  
| Language   | All            |  
| Note       | Blank          |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<span class="paneltitle nomarginbottom">Latest News</span>
<span class="panelsubtitle nomarginbottom">Blog &amp; Social Extension</span>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                                   |  
| :------------------ | :---------------------------------------- |  
| Module Class Suffix | `nomarginbottom nomargintop nopaddingtop` |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/maintop_1.jpeg
[demo3]: assets/maintop_2.jpeg
[demo4]: assets/maintop_3.jpeg