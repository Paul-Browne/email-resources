# email-resources
resources for generating emails


#### A Button
`<center>` will center the button in the middle of the page
```html
<center>
  <table border="0" cellpadding="0" cellspacing="0" style="background-color:blue; border:1px solid blue; border-radius:3px;">
    <tr>
      <td align="center" valign="middle" style="color:#FFFFFF; font-family:Helvetica, Arial, sans-serif; font-size:16px; font-weight:bold; line-height:100%; padding-top:10px; padding-right:20px; padding-bottom:10px; padding-left:20px;">
        <a href="https:///www.google.com" target="_blank" style="color:#FFFFFF; text-decoration:none;">Button!!</a>
      </td>
    </tr>
  </table>
</center>
```

#### White Space

```html
<table border="0" cellspacing="0" cellpadding="0" align="center" width="100%">
    <tr>
      <td height="15" style="font-size: 15px; line-height: 15px;">&nbsp;</td>
    </tr>
</table>
```

#### padding 

`<div>` `<p>` `<a>` - not supported in Outlook

#### width

`<div>` `<p>`  - not supported in Outlook

#### two columns

```html
<table cellpadding="0" cellspacing="0" border="0" width="100%" style="background-color: #ffffff;" bgcolor="#ffffff">
    <tbody>
        <tr>
            <td class="two-column" style="padding: 0px; text-align: center; font-size: 0px;">
                <!--[if (gte mso 9)|(IE)]>
                <table width="100%" style="border-spacing:0;font-family: Calibri, sans-serif;color:#333333;" >
                    <tr>
                        <td width="50%" valign="top" style="padding-top:0;padding-bottom:0;padding-right:0;padding-center:0;" >
                            <![endif]-->
                            <div class="column" style="width: 100%; max-width: 300px; display: inline-block; vertical-align: top;">
                                <table width="100%" style="border-spacing: 0px; font-family: Helvetica, Arial, sans-serif; color: #333333;">
                                    <tbody>
                                        <tr>
                                            <td class="inner" style="padding:0px;">
                                              
                                            </td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        <!--[if (gte mso 9)|(IE)]>
                        </td>
                        <td width="50%" valign="top" style="padding-top:0;padding-bottom:0;padding-right:0;padding-center:0;" >
                            <![endif]-->
                            <div class="column" style="width: 100%; max-width: 300px; display: inline-block; vertical-align: top;">
                                <table width="100%" style="border-spacing: 0px; font-family: Helvetica, Arial, sans-serif; color: #333333;">
                                    <tbody>
                                        <tr>
                                            <td class="inner" style="padding:0px;">
                                                
                                            </td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        <!--[if (gte mso 9)|(IE)]>
                        </td>
                    </tr>
                </table>
                <![endif]-->
            </td>
        </tr>
    </tbody>
</table>
```
