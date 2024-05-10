# **GitHub Eğitimi Programı**

### **Giriş**

-   Intro,
-   Git Intro,
-   Training Intro.

### GitHub Temelleri**

OhMyZsh Config dosyası => [.zshrc](https://github.com/KaramGuliyev/JuniusTechGithub/blob/main/.zshrc)

![](https://gcdnb.pbrd.co/images/e6AExaD0ZbN3.png?o=1)

- Github global config listelemek.

        git config --list / --l

-   GitHub hesabı oluşturma ve ayarlarını yapılandırmak.

        git config --global user.name "Kullanıcı Adı"
        git config --global user.email "kullanici@email.com"

-   Bir repo oluşturma ve temel bilgilerini doldurmak.

	git init 
        git remote add origin <repository_url>
        touch README.md
        git add README.md / .
        git commit -m "First commit"
        git push -u origin main

-   Temel git komutlarını (clone, add, commit, push ve pull) açıklama ve göstermek.

        git clone <repository_url>
        git add .
        git commit -m "Değişiklikleri açıklama"
        git push <origin> <branch>
        
        git pull <origin> <branch>



### İş Akışı ve Dal (Branch) Yönetimi

-   İş akışı (workflow) kavramı : ana dal (main branch), özellik dalı (feature branch) ve birleştirme (merge) işlemleri.

        git branch feature-branch
        git checkout feature-branch
        git checkout -b feature-branch

-   Yeni bir özellik için dal oluşturma, değişiklikler yapma ve ana dala birleştirmek.

        git checkout main
        git merge feature-branch

-   Çakışmaları (conflicts) çözme ve birleştirme adımlarını göstermek.

### İşbirliği ve Proje Yönetimi

![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*dRtIbjRK64BCbXzT7f_rPw.png)

develope/future/api
hotfix/apiFix

-   Proje katkılarını değerlendirme: çekme istekleri (pull requests) oluşturma, gözden geçirme ve birleştirme adımlarını gösterme.

### Soru-Cevap ve Geri Bildirim
