# Python Ders #1


<details> 
<summary> ## Python'ı İndirmek, Yazmak ve Çalıştırmak </summary>

    Python'ı yazmak için öncelikle bilgisayarınızda python3 olup olmadığını kontrol etmeniz gerekiyor. 

    Bunu yapmak da çok basit.

    ### Windows'a python 3'ü indirmek

    Öncelikle Windows + Pause/Break tuş kombinasyonlarına basarak bilgisayarınızın Windows'un 32-bit versyionunu mu 64-bit versiyonu mu çalıştırdığını kontrol edin. Bu size Sistem bilgisini açacak. Açılan bu pencerede "Sistem tipi" satırına bakın. Windows için Python'ı indirmek için resmi siteyi ziyaret edebilirsiniz: [https://www.python.org/downloads/windows/](https://www.python.org/downloads/windows/). "Son Python 3 Sürümü - Python x.x.x" bağlantısına tıklayın. Eğer bilgisayarınız 64-bit versiyon Windows çalıştırıyorsa, Windows x86-64 çalıştırılabilir yükleyici'yi indirin. Değilse, Windows x86 çalıştırılabilir yükleyici'yi indirin. Yükleyiciyi indirdikten sonra, çalıştırmalısınız (üzerine çift tıklayarak) ve oradaki talimatları takip etmelisiniz.

    Dikkat edilmesi gereken bir şey: Yükleme esnasında "Setup" ("Kur") işaretli bir pencere farkedeceksiniz. "Add Python 3.6 to PATH" ("PATH'e Python 3.6'yı ekle) kutucuğunun işaretli olduğundan emin olun ve aşağıda gösterildiği gibi "Install Now" ("Şimdi Yükle") 'a tıklayın:
    
    RESİM

    Önümüzdeki adımlarda, Windows Komut Satırını kullanıyor olacaksınız (ki ayrıca bahsedeceğiz). Şimdilik, bazı komutlar girmeniz gerekirse, Başlat menüsüne gidin ve arama alanına "Komut istemi" yazıp enter'a basın. (Windows'un eski sürümlerinde, komut satırını Başlat menüsü → Windows sistemi → Komut istemi ile başlatabilirsin.) Ayrıca "Çalıştır" penceresi açılana kadar Windows tuşunu basılı tutup "R"-tuşuna basabilirsin. Komut Satırı'nı açmak için, "cmd" yazın ve "Çalıştır" penceresinde enter'a basın.

    Daha sonraki kısımlar bütün işletim sistemlerinde ortak olduğundan en aşağı inerek bir sonraki adıma bakabilirsiniz.

    ### Python'ı Debian ve Ubuntu'ya yüklemek

    Bir terminal açıp sudo apt install python3.6 yazıp enter'a basarak kullanabilirsiniz.

    ### Python'ı Mac OS'e Kurmak

    Python kurulum dosyasını indirmek için resmi siteye gitmelisiniz: [https://www.python.org/downloads/release/python-361/](https://www.python.org/downloads/release/python-361/)

    - *Mac OS X yükleyici* dosyasını indirin,
    - *python-3.6.1-macosx10.6.pkg* 'a çift tıklayarak yükleyiciyi çalıştırın.

    Komut istemini açıp python3 komutunu çalıştırarak yüklemenin başarılı olup olmadığını doğrulayabilirsiniz:

    python3 --version

    Not: Eğer Windows kullanıyorsanız ve python3 bulunamadı hatasını alıyorsanız, python (3 olmadan) komutunu deneyin ve Python 3.6 sürümlerinin olup olmadığını kontrol edin.
    </details>
