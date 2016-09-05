# Veb proqramçılar (mühəndislər) üçün praktiki təhlükəsiz qaydalar

### Kimlər üçün

Vebdə təhlükəsiz insidentlər iki səbəbə görə baş verir - 

1. Veb proqramlaşdırma üzrə fəaliyyətinizi yeni başlamısınız və  MD5/bcrypt arasında fərqini bilmirsiniz.
2. Kifayət qədər təcrübəyə maliksiniz amma təhlükəsiz qaydalara riayət etmirsiniz və ya unutmusunuz.

Buradaki ətraflı izahlar 1-ci kateqoriyalı mühəndislərə kömək edə bilər. Hazırladığımız yoxlama siyahısı isə 2-ci kateqoriyalı mühəndislər üçün faydalı ola bilər. Əlbətdə ki, bu hərtərəfli instruksiya deyil. Amma burada qeyd olunan problemlər ən yayılmış texniki xətalara aiddir.


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
6.1 Giriş verilənlərin təhlükəsiz əldə edilməsi  
6.2 Çıxış verilənlərin təhlükəsiz əldə edilməsi  
6.3 Saytlar arası skripting (XSS)  
6.4 Müdaxilə hücumları (İnyeksiyalar)  
6.5 İstifadçilərin yüklənmələri  
6.6 Müdaxilələrə dayanaqlılıq
7. Açıq mətn != Kodlaşdırma != Şifrələmə != Haşlama  
7.1 Ümumi kodlaşdırma metodları  
7.2 Şifrələmə  
7.3 Haşlar və bir tərəfli funksiyalar  
7.4 Haş funksiyaların sürət cədvəli
8. Parollar: dadada, 123456 və password123  
8.1 Parolların qaydaları  
8.2 Parolları necə yerləşdirmək lazımdır  
8.3 Parolsuz həyat
9. Açıq açar kriptoqrafiyası
10. Sessiyalar: Məni yadda saxlıyın  
10.1 Halını (state) harda saxlamaq lazımdır?  
10.2 Etibarsız sessiyalar  
10.3 Kukilər
11. Veb başlıqların təhlükəsizliyi  
11.1 Veb başlıqralrın qorunması  
11.2 Kənar kodlar üçün verilənlərin tamlığını yoxlanılması  
11.3 Sertifiaktların Pinninqi (Certificate Pinning)
12. Sazlama xətaları    
12.0 Provisioning in cloud: Ports, Shodan & AWS
12.1 Honey, you left the debug mode on  
12.2 Texniki qeydlər  
12.3 Müşahidə  
12.4 Minimal səlahiyyət prinsipi (least privilege)  
12.5 Kaptçalar və istifadə məhdudiyyətlər  
12.6 Parolları və gizli məlumatları faylda saxlanma  
12.7 DNS: alt domeynlər və unudulmuş şəxsi səhifələr  
12.7 Yeniləmə və Patçlama  
13. Hücumlar: Pis oğlanlar nə zaman gəlir  
13.1 Clickjacking  
13.2 Saytlar arası sorğuların saxtalaşdırması (CSRF)  
13.3 Xidmətdən İmtina  
13.4 Server tərəf sorğuların saxtalaşdırması
14. [İnternet saytlarda aşkar olunan boşluqların statistikası](vulnerabilities-stats.md)   
15. On reinventing the wheel, and making it square  
15.1 Python üçün təhlükəsiz kitabxanalar və paketlər  
15.2 Node/JS üçün təhlükəsiz kitabxanalar və paketlər  
15.3 Öyrənmə mənbələri
16. Təhlükəsiz gigiyenasının dəstəklənməsi
17. Təhlükəsizlik və rahat istifadə etmə üsulları
18. Back to Square 1: The Security Checklist explained

