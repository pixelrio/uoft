# Examples of component usage
http://engage.utoronto.ca/site/MessageViewer?em_id=10502.0&dlv_id=14441&printer_friendly=1
http://engage.utoronto.ca/site/MessageViewer?em_id=8281.0&dlv_id=14441&printer_friendly=1
http://engage.utoronto.ca/site/MessageViewer?em_id=7383.0&dlv_id=14441&printer_friendly=1

# Title block
```
<!-- Featured Event Title : BEGIN -->
                <tr>
                    <td style="background-color: #ffffff;">
                        <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%" style="max-width: 640px;">
                            <tr>
                                <td style="padding: 20px; font-family: sans-serif; font-size: 36px; line-height: 42px !important;font-weight: bold; color: #1E3765;">
								<table border="0" cellpadding="0" cellspacing="0" role="presentation" style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; margin: 0 !important" width="70">
<tr>
<td class="divider_inner" style="font-size: 1px; line-height: 1px; border-top: 7px solid #007FA3; text-align:left;"><span></span></td>
</tr>
</table> 
									 <p style="margin: 5px 0 10px; font-family: Arial, sans-serif; font-size: 18px; font-weight: bold; color: #007FA3; line-height: 22px;">
                                        EVENT TAG
                                    </p> 
                                    <h1 style="margin: 0; font-size: 36px; line-height: 42px !important;font-weight: bold;">
                                        <a href="https://example.com" style="font-size: 40px; line-height: 44px !important;font-weight: bold; color: #000000;">
                                            FEATURED EVENT TITLE
                                        </a>
                                    </h1>
                                </td>
                            </tr>
                        </table>
                    </td>
                </tr>                
                <!-- Featured Event Title : END -->
```
# Image block
```
<!-- Image : BEGIN -->
                <tr>
                    <td style="background-color: #ffffff; color: #ffffff; text-align: center; padding-left: 20px !important; padding-top: 10px !important; padding-right: 20px !important; padding-bottom: 20px !important;">
                        <a href="https://example.com" style="text-decoration: none;">
                            <img src="https://placehold.co/640x400" width="640" height="" alt="ALT TEXT" border="0" style="width: 100%; max-width: 640px; height: auto; background: #1e3765; margin: auto; display: block;" class="g-img">
                        </a>
                    </td>
                </tr>
                <!-- Image : END -->
```
# 1 column text + button
```
 <!-- 1 Column Text + Button : BEGIN -->
                <tr>
                    <td style="background-color: #ffffff;">
                        <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%">
                          
                            <tr>
                                <td style="margin:0; padding: 0px 20px; font-family: Arial, sans-serif; font-size: 18px; color: #000000; line-height: 22px;">
								<p style="margin: 10px 0 20px 0; color: #000000; font-size: 18px; line-height:21px;"><strong>Date</strong><br>Time<br>
Location <br>
Cost</p>
									
                                      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean rhoncus bibendum elit sed facilisis. Sed et sollicitudin turpis, sit amet aliquet urna. Aenean in elementum risus. Aenean iaculis, dui a eleifend faucibus, metus nisi volutpat felis, quis tincidunt nisl nisl at arcu. Maecenas pellentesque, justo et cursus feugiat, ex nisi ultricies eros, nec dapibus quam sapien at odio. Vestibulum laoreet urna nisi, non sollicitudin nibh vestibulum et. <br><br>
<strong>Lorem ipsum dolor sit amet</strong>
<ul style="margin:0; margin-left: 20px; padding:0; font-family: Arial, sans-serif !important; color:#000000; font-size:18px; line-height:22px;" align="left" type="disc">		<li style="font-family: Arial, sans-serif !important; color:#000000; font-size:18px; line-height:22px;">Lorem ipsum dolor sit amet</li>
<li style="font-family: Arial, sans-serif !important; color:#000000; font-size:18px; line-height:22px;">Mauris et purus a nisl posuere blandit.</li>
<li style="font-family: Arial, sans-serif !important; color:#000000; font-size:18px; line-height:22px;">Duis ut quam venenatis, pharetra augue vel, accumsan nunc.</li>
<li style="font-family: Arial, sans-serif !important; color:#000000; font-size:18px; line-height:22px;">Proin ac ante convallis nisi laoreet auctor nec quis nulla.</li>
</ul>
                               
                                </td>
                            </tr>
                            <tr>
                                <td style="margin:0; padding: 20px 20px 25px;">
                                    <!-- Button : BEGIN -->
                                    <table align="center" role="presentation" cellspacing="0" cellpadding="0" border="0" style="margin: auto; border-radius: 25px;">
                                        <tr>
                                            <td class="button-td button-td-primary" style="border-radius: 25px; background: #047296;">
                                                <td class="button-td button-td-primary" style="background: #047296; border-radius: 25px;">
                                                    <a class="button-a button-a-primary" style="background: #047296; border: 1px solid #047296; font-family: Arial, sans-serif; font-size: 16px; line-height: 14px; font-weight:bold; text-decoration: none; padding: 15px 10px; color: #ffffff; display: block; border-radius: 25px; width: 200px; text-align: center;" href="https://example.com">Primary CTA</a>
                                                </td>
											</td>
                                        </tr>
                                    </table>
                                    <!-- Button : END -->
                                </td>
                            </tr>
                        </table>
                    </td>
                </tr>
                <!-- 1 Column Text + Button : END -->
```
# Two column, image left, text right
```
<!-- Two column, image left, text right : BEGIN -->
                <tr>
                    <td align="center" valign="top" style="font-size:0; padding: 0px 10px 10px; background-color: #ffffff;">
                        <!--[if mso]>
                        <table role="presentation" border="0" cellspacing="0" cellpadding="0" width="620">
                        <tr>
                        <td valign="top" width="310">
                        <![endif]-->
                        <div style="display:inline-block; margin: 0 -1px; width:100%; min-width:200px; max-width:310px; vertical-align:top;" class="stack-column">
                            <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%">
                                <tr>
                                    <td style="padding: 10px;">
                                        <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%" style="font-size: 14px; text-align: left;">
                                            <tr>
                                                <td>
                                                    <a href="https://secureca.imodules.com/s/731/form-blank/index.aspx?sid=731&gid=1&pgid=21013&cid=34894&utm_source=DUA&utm_medium=email&utm_campaign=careerwebinar&utm_content=image">
                                                        <img src="https://placehold.co/290" width="290" height="" border="0" alt="A U of T grad smiling and looking to her left" style="width: 100%; height: auto; background: #D5D5D5; font-family: sans-serif; font-size: 15px; line-height: 20px; color: #555555;" class="center-on-narrow">
                                                    </a>
                                                </td>
                                            </tr>

                                        </table>
                                    </td>
                                </tr>
                            </table>
                        </div>
                        <!--[if mso]>
                        </td>
                        <td valign="top" width="310">
                        <![endif]-->
                        <div style="display:inline-block; margin: 0 -1px; width:100%; min-width:200px; max-width:310px; vertical-align:top;" class="stack-column">
                            <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%">
                                <tr>
                                    <td style="padding: 10px;">
                                        <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%" style="font-size: 14px;text-align: left;">
                                            <tr>
                                                <td dir="ltr" style="font-family: sans-serif; font-size: 18px; line-height: 28px; color: #000000; padding: 0 10px 10px 10px 0; text-align: left;">
													<p style="margin:5px 0 0; font-family: sans-serif; font-size: 24px; line-height: 30px; font-weight: bold;">Name<br>
Title</p>
                                                    <p style="margin: 30px 0 0 0; color: #000000; font-size: 18px; line-height:21px;"><strong>Tuesday, June 27, 2023</strong><br>1-2 p.m. EDT<br>
Location<br>
Cost<br>
<a href="https://example.com" style="text-decoration: underline; color:#007FA3;">CTA text</a></p>
                                                   
                                                </td>
                                            </tr>
                                                
                                        </table>
                                    </td>
                                </tr>
                            </table>
                        </div>
                        <!--[if mso]>
                        </td>
                        </tr>
                        </table>
                        <![endif]-->
                    </td>
                </tr>
                <!-- Two column, image left, text right : END -->
```

# CTA block
```
<!-- CTA Block : BEGIN -->
                <tr>
                    <td style="background-color: #FFFFFF; padding: 20px;">
                        <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%" style="max-width: 640px; background-color: #CCEAF2;">
                            <tr>
                                <td style="font-family: sans-serif; font-size: 18px; line-height: 26px; color: #000000; text-align: center;">
                                    <h2 style="margin: 30px 0 0 0; font-size: 30px; line-height: 34px;font-weight: bold; font-family:'tradegothiclt', sans-serif;">CTA Block</h2>
                                    <p style="padding: 0 20px;margin: 20px 0;">Duis ut quam venenatis, pharetra augue vel, accumsan nunc.</p>
                                </td>
                            </tr>
                            <tr>
                                <td style="padding-bottom: 30px;">
                                  <!-- Button : BEGIN -->
                                  <table align="center" role="presentation" cellspacing="0" cellpadding="0" border="0">
                                    <tr>
                                      <td class="button-td button-td-primary" style="border-radius: 25px; background: #117FA3;">
                                        <a class="button-a button-a-primary" href="https://example.com" style="background: #117FA3; border: 2px solid #117FA3; font-family: sans-serif; font-size: 14px; line-height: 16px; text-decoration: none; padding: 12px 26px; color: #ffffff; display: block; border-radius: 25px; width: 160px; text-align: center;" width="200">
                                          <strong>CTA button </strong>
                                        </a>
                                      </td>
                                    </tr>
                                  </table>
                                  <!-- Button : END -->
                                </td>
                              </tr>
                        </table>
                    </td>
                </tr>
                <!-- Sample CTA Block : END -->
```
# Prefooter block
```
<!-- Prefooter block : BEGIN -->
                <tr>
                    <td align="center" valign="top" style="font-size:0; padding: 10px; background-color: #E5F2F6;">
                        <!--[if mso]>
                        <table role="presentation" border="0" cellspacing="0" cellpadding="0" width="620">
                        <tr>
                        <td valign="top" width="310">
                        <![endif]-->
                        <div style="display:inline-block; margin: 0 -1px; width:100%; min-width:200px; max-width:310px; vertical-align:top;" class="stack-column">
                            <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%">
                                <tr>
                                    <td style="padding: 10px;">
                                        <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%" style="font-size: 14px; text-align: left;">
                                            <tr>
                                                <td>
                                                    <a href="https://example.com">
                                                        <img src="https://placehold.co/290" width="290" height="" border="0" alt="A U of T grad smiling and looking to her left" style="width: 100%; height: auto; background: #D5D5D5; font-family: sans-serif; font-size: 15px; line-height: 20px; color: #555555;" class="center-on-narrow">
                                                    </a>
                                                </td>
                                            </tr>

                                        </table>
                                    </td>
                                </tr>
                            </table>
                        </div>
                        <!--[if mso]>
                        </td>
                        <td valign="top" width="310">
                        <![endif]-->
                        <div style="display:inline-block; margin: 0 -1px; width:100%; min-width:200px; max-width:310px; vertical-align:top;" class="stack-column">
                            <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%">
                                <tr>
                                    <td style="padding: 10px;">
                                        <table role="presentation" cellspacing="0" cellpadding="0" border="0" width="100%" style="font-size: 14px;text-align: left;">
                                            <tr>
                                                <td dir="ltr" style="font-family: sans-serif; font-size: 18px; line-height: 28px; color: #1E3765; padding: 0 10px 10px 10px 0; text-align: left;">
                                                    <h2 style="margin: 0; font-family: sans-serif; font-size: 32px; line-height: 36px; font-weight: bold;"><a href="https://example.com" style="color: #1E3765;">Prefooter example</a></h2>

                                                    <p style="margin: 10px 0 10px 0; color: #1E3765;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean rhoncus bibendum elit sed facilisis. Sed et sollicitudin turpis, sit amet aliquet urna. Aenean in elementum risus.  </p>
                                                </td>
                                            </tr>
                                            <tr>
                                                <td>
                                                <!-- Button : BEGIN -->
                                                <table align="left" role="presentation" cellspacing="0" cellpadding="0" border="0" class="mobile-btn">
                                                    <tr>
                                                    <td class="button-td button-td-primary button-white" style="border-radius: 25px; background: #FFFFFF;">
                                                        <a class="button-a button-a-primary button-white" href="https://alumni.utoronto.ca/index.php/benefits/career-development?utm_source=DUA&utm_medium=email&utm_campaign=careerwebinar&utm_content=button" style="background: #FFFFFF;border: 2px solid #000000;font-family: sans-serif;font-size: 14px;line-height: 16px;text-decoration: none;padding: 14px 26px;color: #007fa3;display: block;border-radius: 25px;width: 200px;text-align: center;" width="200">
                                                        <strong>Secondary CTA</strong>
                                                        </a>
                                                    </td>
                                                    </tr>
                                                </table>
                                                <!-- Button : END -->
                                                </td>
                                              </tr>        
                                        </table>
                                    </td>
                                </tr>
                            </table>
                        </div>
                        <!--[if mso]>
                        </td>
                        </tr>
                        </table>
                        <![endif]-->
                    </td>
                </tr>
                <!-- Prefooter block : END -->
```
# Divider
```
<!-- Divider : BEGIN -->
                <tr>
                    <td style="padding: 0; margin: 0; width: 100%;">
                        <table style="width: 100%; background: #FFFFFF;" border="0" cellspacing="0" cellpadding="0">
                            <tr>
                                <td style="padding: 10px 20px;">
                                    <table style="width: 100%; background: #FFFFFF;" border="0" cellspacing="0" cellpadding="0">
                                        <tr>
                                            <td style="border-bottom: 1px solid #010000; text-align: center; line-height: 1px; font-size: 22px; padding: 0;">&nbsp;</td>
                                        </tr>
                                    </table>
                                </td>
                            </tr>
                        </table>
                    </td>
                </tr>
               
                <!-- Divider : END -->
```
