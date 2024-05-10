# **GitHub Eğitimi Programı**

### **Giriş**
-   Intro,
-   Git Intro,
-   Training Intro.

### GitHub Temelleri**



- Github global config listeleme

        git config --list / --l

-   GitHub hesabı oluşturma ve ayarlarını yapılandırma.

        git config --global user.name "Kullanıcı Adı"
        git config --global user.email "kullanici@email.com"

-   Bir repo oluşturma ve temel bilgilerini doldurma.

	    git init 
        git remote add origin <repository_url>
        touch README.md
        git add README.md / .
        git commit -m "First commit"
        git push -u origin main

-   Temel git komutlarını (clone, add, commit, push) açıklama ve gösterme.

        git clone <repository_url>
        git add .
        git commit -m "Değişiklikleri açıklama"
        git push <origin> <branch>

### İş Akışı ve Dal (Branch) Yönetimi

-   İş akışı (workflow) kavramını açıklama: ana dal (main branch), özellik dalı (feature branch) ve birleştirme (merge) işlemleri.

        git branch feature-branch
        git checkout feature-branch
        git checkout -b feature-branch

-   Yeni bir özellik için dal oluşturma, değişiklikler yapma ve ana dala birleştirme.

        git checkout main
        git merge feature-branch

-   Çakışmaları (conflicts) çözme ve birleştirme adımlarını gösterme.

### İşbirliği ve Proje Yönetimi

![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*dRtIbjRK64BCbXzT7f_rPw.png)

-   Proje katkılarını değerlendirme: çekme istekleri (pull requests) oluşturma, gözden geçirme ve birleştirme adımlarını gösterme.

### Soru-Cevap ve Geri Bildirim
