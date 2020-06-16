# OTRS-Goole-reCaptcha-for-Sign-Up-Form
- For OTRS CE v6.0
- Google reCaptcha at OTRS customer portal (sign-up form)		
- Modification files (based on OTRS 6.0.19) has been tag with :

	#begin recaptcha  
	CODE	
	#end recaptcha  
	

1. create and configure captcha V2 https://www.google.com/recaptcha/admin  
2. Install Captcha::reCAPTCHA::V2 via cpan  
3. Update Site Key at Admin > System Configuration > GoogleCaptcha::SiteKey  
4. Update Secret Key at Admin > System Configuration > GoogleCaptcha::SecretKey  


Simulation: Signup without completing captcha    
[![captcha1.png](https://i.postimg.cc/ZKYQ4NkF/captcha1.png)](https://postimg.cc/QVPmqHdH)  

[![captcha2.png](https://i.postimg.cc/jSLkJrSD/captcha2.png)](https://postimg.cc/3kQZPVph)  