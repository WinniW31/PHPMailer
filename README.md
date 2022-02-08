![PHPMailer](https://raw.github.com/PHPMailer/PHPMailer/master/examples/images/phpmailer.png)

# PHPMailer – A full-featured email creation and transfer class for PHP (EAI Suppported version modify by [THNIC Foundation](https://www.thnic.or.th))

## Attention
1. This is not a stable PHPMailer version. 
2. This version modified and used by [THNIC Foundation](https://www.thnic.or.th) to make PHPMailer can send and received [EAI email](https://xn--12cn4frcvb5f.xn--o3cw4h/%e0%b8%8a%e0%b8%b7%e0%b9%88%e0%b8%ad%e0%b8%ad%e0%b8%b5%e0%b9%80%e0%b8%a1%e0%b8%a5%e0%b8%a0%e0%b8%b2%e0%b8%a9%e0%b8%b2%e0%b9%84%e0%b8%97%e0%b8%a2-eai/).
3. This is a proof of concept version (POC)
4. You can find a stable PHPMailer verion [here](https://github.com/PHPMailer/PHPMailer).
5. Please feel free to forked, modified and use it on your purpose.

## What we have done
1. In src/SMTP.php, at function mail(), we change and fix to use SMTPUTF8.
2. In src/PHPMailer.php, at function preSend(), we comment out punyencodeAddress() function and decide not to use it as it make Thai email cannot send.

## License
This software is distributed under the [LGPL 2.1](http://www.gnu.org/licenses/lgpl-2.1.html) license, along with the [GPL Cooperation Commitment](https://gplcc.github.io/gplcc/). Please read [LICENSE](https://github.com/PHPMailer/PHPMailer/blob/master/LICENSE) for information on the software availability and distribution.

