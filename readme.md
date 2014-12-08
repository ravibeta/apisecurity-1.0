# OAuth implementors require jumping through hoops to sign and make a request.
# Here we simply propose the use of an OTP token to sign and make a request.
# implemented in totp.py
# for more detail, please visit : http://1drv.ms/13YBENz
otp = OneTimePasswordAlgorithm()
import hashlib
otp.generateTOTP('90AB891C', '123465539', '6', hashlib.sha256)
'857652'
