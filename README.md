# aliyun_sms_config
安装短信服务vendor类
# 使用方法
引入 use Zzx\config\AliSms;  
实例化  new AliSms();  
使用对象 $alisms->sendSms($mobile,$this->TemplateCode,$smsParam,$this->config,$this->OutId);  
参数一：接收验证码的手机号  
参数二：短信模板id  
参数三：发送的验证码，例如：array('code'=>'1234');  
参数四：基本配置，例如：array('access_key'=>'123456','access_secret'=>'123456','sign_name'=>'必填，签名模板')  
参数五：短信流水号  

