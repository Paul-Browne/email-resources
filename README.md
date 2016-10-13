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


#### bordered text

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional //EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	<meta http-equiv="X-UA-Compatible" content="IE=edge" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
</head>
  <body>

			<table border="0" cellpadding="0" cellspacing="0" style="border-spacing: 0; border-collapse: collapse;">
              <tr>
                  <td width="25" height="127" valign="top" style="font-size:0;">
                      <img style="vertical-align:middle;display:block" width="25" height="127" src="http://image.email.finnair.com/lib/fe92127276640d7c7d/m/2/box-left.png" />
                    </td>
                <td>
                  <table border="0" cellpadding="0" cellspacing="0" style="border-spacing: 0; border-collapse: collapse;">
                    <tr>
                        <td width='300' height="2" valign="top" style="font-size:0;">
                            <img style="vertical-align:middle;display:block" width="300" height="2" src="http://image.email.finnair.com/lib/fe92127276640d7c7d/m/2/box-top-600.png" />
                          </td>
                    </tr>
                    <tr>
                      <td width='300' height='120' style="background:white">ggg sdf sdf sdf sd fsd f<br> asd asd as das d asd as </td>
                    </tr>
                    <tr>
                        <td width='300' height="5" valign="top" style="font-size:0;">
                            <img style="vertical-align:middle;display:block" width="300" height="5" src="http://image.email.finnair.com/lib/fe92127276640d7c7d/m/2/box-bottom-600.png" />
                        </td>
                    </tr>
                  </table>
                </td>
                <td width="46" height="127" valign="top" style="font-size:0;">
                    <img style="vertical-align:middle;display:block" width="46" height="127" src="http://image.email.finnair.com/lib/fe92127276640d7c7d/m/2/box-right.png" />
                  </td>
              </tr>
            </table>
  </body>
</html>
```




