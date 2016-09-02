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
                                                <table align="center" class="contents" style="border-spacing: 0px; font-family: Helvetica, Arial, sans-serif; color: #333333; width: 100%; font-size: 14px; text-align: center;">
                                                    <tbody>
                                                        <tr>
                                                            <td style="padding: 0px;">
                                                                <a href="%%=RedirectTo(Lookup(@ChangeDE, 'PARTNER3 G link', 'LanguageCode', @ChangeLC))=%%" target="_blank" style="text-decoration: none;">
                                                                    <img src="%%=TreatAsContent(@PARTNER3)=%%"" width="150"  style="border-width: 0px; width: 150px; height: auto; Margin:0 auto;"  />
                                                                </a>
                                                                <table border="0" cellspacing="0" cellpadding="0" align="center" width="100%">
                                                                    <tr>
                                                                        <td height="20" style="font-size: 20px; line-height: 20px;">&nbsp;</td>
                                                                    </tr>
                                                                </table>
                                                                <a href="%%=RedirectTo(Lookup(@ChangeDE, 'PARTNER3 G link', 'LanguageCode', @ChangeLC))=%%" style="display:block; width:240px; height:63px; font-size: 14px; line-height: 21px; font-family: 'Helvetica', 'Arial', sans-serif; color:#0b2273; Margin: 0 auto;">
                                                                    %%=TreatAsContent(Lookup(@ChangeDE, 'PARTNER3 G copy', 'LanguageCode', @ChangeLC))=%% 
                                                                </a>                                                                            
                                                                <table border="0" cellspacing="0" cellpadding="0" align="center" width="100%">
                                                                    <tr>
                                                                        <td height="40" style="font-size: 40px; line-height: 40px;">&nbsp;</td>
                                                                    </tr>
                                                                </table>
                                                            </td>
                                                        </tr>
                                                    </tbody>
                                                </table>
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
                                                <table align="center" class="contents" style="border-spacing: 0px; font-family: Helvetica, Arial, sans-serif; color: #333333; width: 100%; font-size: 14px; text-align: center;">
                                                    <tbody>
                                                        <tr>
                                                            <td style="padding: 0px;">
                                                                <a href="%%=RedirectTo(Lookup(@ChangeDE, 'PARTNER4 G link', 'LanguageCode', @ChangeLC))=%%" target="_blank" style="text-decoration: none;">
                                                                    <img src="%%=TreatAsContent(@PARTNER4)=%%"" width="150"  style="border-width: 0px; width: 150px; height: auto; Margin:0 auto;"  />
                                                                </a>
                                                                <table border="0" cellspacing="0" cellpadding="0" align="center" width="100%">
                                                                    <tr>
                                                                        <td height="20" style="font-size: 20px; line-height: 20px;">&nbsp;</td>
                                                                    </tr>
                                                                </table>
                                                                <a href="%%=RedirectTo(Lookup(@ChangeDE, 'PARTNER4 G link', 'LanguageCode', @ChangeLC))=%%" style="display:block; width:240px; height:63px; font-size: 14px; line-height: 21px; font-family: 'Helvetica', 'Arial', sans-serif; color:#0b2273; Margin: 0 auto;">
                                                                    %%=TreatAsContent(Lookup(@ChangeDE, 'PARTNER4 G copy', 'LanguageCode', @ChangeLC))=%% 
                                                                </a>                                                                            
                                                                <table border="0" cellspacing="0" cellpadding="0" align="center" width="100%">
                                                                    <tr>
                                                                        <td height="40" style="font-size: 40px; line-height: 40px;">&nbsp;</td>
                                                                    </tr>
                                                                </table>
                                                            </td>
                                                        </tr>
                                                    </tbody>
                                                </table>
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
