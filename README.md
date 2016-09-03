# Veb proqramçılar (mühəndislər) üçün praktiki təhlükəsiz qaydalar

### Kimlər üçün

Vebdə təhlükəsiz insidentlər iki səbəbə görə baş verir - 

1. Veb proqramlaşdırma üzrə fəaliyyətinizi yeni başlamısınız və  MD5/bcrypt arasında fərqini bilmirsiniz.
2. Kifayət qədər təcrübəyə maliksiniz amma təhlükəsiz qaydalara riayət etmirsiniz və ya unutmusunuz.

Buradaki detallı izahlar 1-ci kateqoriyalı mühəndislərə kömək edə bilər. Hazırladığımız yoxlama siyahısı isə 2-ci kateqoriyalı mühəndislər üçün faydalı ola bilər. Əlbətdə ki, bu hərtərəfli instruksiya deyil. Amma burada qeyd olunan problemlər ən yayılmış texniki xətalara aiddir.


### Mündəricat

1. [Təhlükəsiz qaydaların siyahısı](security-checklist.md)
2. Nələr yanlış gedə bilər?
3. Məlumatların təhlükəsiz ötürülməsi: HTTPS nədir?
4. Autentifikasiya: Mən kiməm? Sən kimsən?
4.1 Formlara görə autentifikasiya  
4.2 Sadə autentifikasiya  
4.3 Bir neçə faktorlu autentifiaksiya  
4.4 Təhlükəli tekst mesajları istifadə etmiyək. HOTP & TOTP nədir?   
4.5 Parolları necə yenilənmək lazımdır
5. Avtorizasiya: Mən nə edə bilərəm?  
5.1 Tokenli avtorizasiya  
5.2 OAuth & OAuth2  
5.3 JWT
6. Giriş verilənlərin yoxlaması: Giriş verilənlərə heç zaman etibar etməyin  
6.1 Validating and Sanitizing Inputs  
6.2 Sanitizing Outputs  
6.3 Cross Site Scripting  
6.4 Injection Attacks  
6.5 User uploads  
6.6 Tamper-proof user inputs
7. Plaintext != Encoding != Encryption != Hashing  
7.1 Ümumi kodlaşdırma metodları  
7.2 Şifrələmə  
7.3 Haşlar və bir tərəfli funksiyalar  
7.4 Haş funksiyaların sürət cədvəli
8. Parollar: dadada, 123456 və password123  
8.1 Parolların qaydaları  
8.2 Parolları necə yerləşdirmək lazımdır  
8.3 Parolsuz həyat
9. Açıq açar kriptoqrafiyası
10. Sessiyalar: Məni yadda saxlıyıne  
10.1 Where to save state?  
10.2 Invalidating sessions  
10.3 Cookie monster & you
11. Fixing security, one header at a time  
11.1 Secure web headers  
11.2 Data integrity check for 3rd party code  
11.3 Certificate Pinning
12. Sazlama xətaları    
12.0 Provisioning in cloud: Ports, Shodan & AWS
12.1 Honey, you left the debug mode on  
12.2 Texniki qeydləri yazma  
12.3 Müşahidə  
12.4 Principle of least privilege  
12.5 Rate limiting & Captchas  
12.6 Storing project secrets and passwords in a file    
12.7 DNS: Of subdomains and forgotten pet-projects  
12.7 Patching & Updates  
13. Attacks: When the bad guys arrive  
13.1 Clickjacking  
13.2 Cross Site Request Forgery  
13.3 Xidmətdən İmtina  
13.4 Server Side Request Forgery
14. [Stats about vulnerabilities discovered in Internet Companies](vulnerabilities-stats.md)   
15. On reinventing the wheel, and making it square  
15.1 Security libraries and packages for Python  
15.2 Security libraries and packages for Node/JS  
15.3 Öyrənmə mənbələri
16. Maintaining a good security hygiene
17. Təhlükəsizlik və rahat istifadə etmə
18. Back to Square 1: The Security Checklist explained

