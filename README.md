# Açıq məlumatlar" portalının iştirakçı təlimatı

Bu təlimat [**CKAN 2.10.7 Overview**](https://docs.ckan.org/en/2.10/) sənədinə əsaslanaraq hazırlanmış və “Açıq Məlumatlar” portalının məlumat idarəetmə sistemindən istifadə edən iştirakçılar üçün nəzərdə tutulmuşdur. Təlimatda iştirakçıların yerinə yetirəcəyi bütün əməliyyatlar ətraflı izah edilmişdir. Bu, onların məlumatların paylaşılması və idarə olunması prosesini effektiv və düzgün şəkildə icra etməsinə kömək edəcək.

# "Açıq Məlumatlar" portalı nədir

**"Açıq Məlumatlar" portalı** ictimaiyyət üçün açıq olan məlumatların toplanması, idarə olunması və paylaşılması üçün rəqəmsal platformadır. Portal şəffaflığı artırır, məlumatlardan istifadəyə şərait yaradır və innovasiyalara dəstək verir. Adətən Məlumat idarəetmə sistemi (CKAN) əsasında işləyir və müxtəlif formatlarda məlumat təqdim edir.

# Əsas anlayışlar

Aşağıdakı cədvəl sizə portalda yer alan Anlayışlar və biznes terminləri haqqında ümumi məlumat verir.

<table><tbody><tr><th><p><strong>Əsas</strong></p><p><strong>anlayışlar</strong></p></th><th><p><strong>Açıqlama</strong></p></th></tr><tr><td><p><strong>Open Data</strong></p><p><strong>(Açıq məlumat)</strong></p></td><td><p>Açıq şəkildə paylaşılan və hər kəsin istifadə edə biləcəyi məlumatlardır.</p></td></tr><tr><td><p><strong>CKAN</strong></p></td><td><p>Açıq mənbəli məlumat idarəetmə sistemi olub, məlumat dəstlərinin saxlanması, paylaşılması və yayımlanması üçün istifadə olunur.</p></td></tr><tr><td><p><strong>Metadata</strong></p><p><strong>(Metaməlumatlar)</strong></p></td><td><p>Məlumat dəstləri haqqında məlumatları təsvir edən məlumatlar.</p></td></tr><tr><td><p><strong>Dataset</strong></p><p><strong>(Məlumat Dəsti)</strong></p></td><td><p>Müəyyən bir mövzuya aid məlumatların toplusu. Məsələn, bir bölgənin cinayət statistikası və ya hökumət departamentinin xərcləri haqqında məlumatlar.</p></td></tr><tr><td><p><strong>Source</strong></p><p><strong>(Mənbə)</strong></p></td><td><p>İdarəetmə sistemində məlumat dəstinin mənşəyini və ya məlumatın haradan alındığını göstərmək üçün nəzərdə tutulub.</p></td></tr><tr><td><p><strong>Resource</strong></p><p><strong>(Resurs)</strong></p></td><td><p>Məlumat dəstindəki faktiki məlumat faylları və ya məlumat mənbələri. Bu fayllar CSV, Excel formatları (XLS, XLSX), XML, PDF və ya digər formatlarda ola bilər.</p></td></tr><tr><td><p><strong>Activity Stream</strong></p><p><strong>(Fəaliyyət Axını)</strong></p></td><td><p>Məlumat dəstləri və təşkilatlar üzərində aparılan son fəaliyyətlərin xronoloji siyahısı.</p></td></tr><tr><td><p><strong>Member</strong></p></td><td><p>Təşkilatın <strong>private (yanlızca məlumat idarəetmə sistemindən əlçatan olan) məlumat dəstərini</strong> görə bilər.</p></td></tr><tr><td><p><strong>Editor</strong></p></td><td><p><strong>Member</strong>-in bütün funksiyalarını yerinə yetirə bilər.<br>Əlavə olaraq:</p><ul><li>Təşkilata yeni <strong>Məlumat dəstləri</strong> əlavə edə bilər.</li><li>Təşkilatdakı istənilən <strong>Məlumat dəstini</strong> redaktə və ya silə bilər.</li><li><strong>Məlumat dəstləri</strong> <strong>public</strong> və ya <strong>private</strong> edə bilər.</li></ul></td></tr><tr><td><p><strong>Admin</strong></p></td><td><p><strong>Editor</strong>-un bütün funksiyalarını yerinə yetirə bilər.<br>Əlavə olaraq:</p><ul><li>Təşkilata yeni İştirakçılar əlavə edə bilər və həmin iştirakçıların <strong>Member</strong>, <strong>Editor</strong> və ya <strong>Admin</strong> olmasını seçə bilər.</li><li>Təşkilatdakı istənilən iştirakçıların rolunu dəyişdirə bilər (digər <strong>Admin</strong>-lər də daxil olmaqla).</li><li><strong>Member</strong>, <strong>Editor</strong> və ya digər <strong>Admin</strong>-ləri təşkilatdan silə bilər.</li><li>Təşkilat haqqında məlumatları redaktə edə bilər (ad, təsvir, şəkil və s.).</li><li>Təşkilatı tamamilə silə bilər.</li></ul></td></tr><tr><td><p><strong>Collaborator</strong></p><p><strong>(Əməkdaş)</strong></p></td><td><p>Bu funksiya Məlumat dəsti səviyyəsində icazələrin idarə edilməsini təmin edir Bu zaman uyğun icazəsi olan Əməkdaşlar, istənilən fərdi Məlumat dəsti üzərində verilən rola uyğun əməliyyatlar icra edə bilir.</p></td></tr><tr><td><p><strong>Update frequency</strong><br><strong>(Yenilənmə tezliyi)</strong></p></td><td><p>Yenilənmə tezliyi məlumat dəstinin nə qədər zamandan bir yeniləndiyini bizə göstərir.<br>Nümunə: yenilənmə tezliyi – 1 ay, yenilənmə tezliyi – 3 saat.</p></td></tr></tbody></table>

# Bölmələr

## Datasets – Məlumat dəstləri

Datasets bölməsində məlumat idarəetmə sistemində yer alan bütün Məlumat dəstləri görmək, aid olduğu quruma Məlumat dəsti əlavə etmək, onları dəyişdirmək, silmək və digər əməliyyatları həyata keçirmək mümkündür.

## Organizations - Təşkilatlar

Hər bir Məlumat dəsti bir organization-a aiddir və onu həmin təşkilat idarə edir. Hər bir təşkilatda aşağıda yer alan İştirakçı rolları mövcuddur: Admin, Editor və Member

## Groups - Kateqoriyalar

Bu bölmə idarə etmə sistemində olan məlumat dəstlərinin kolleksiyalarını (kateqoriyalarını) yaratmaq və idarə etmək üçün istifadə olunur.

## Data Requests - Məlumat Sorğuları

Məlumat sorğusu (data request) bir təşkilatdan müəyyən məlumatın açıqlanması yöndə olan müraciətlərin toplandığı bölmədir.

## Showcase - İstifadə Nümunələri

Bu bölmə, məlumat dəstlərinin tətbiq olunma nümunələrini təqdim edir.

# 1\. Məlumat idarəetmə sisteminin istifadəsi

## 1.1. Qeydiyyatdan keçmək

1. İştirakçıya göndərilən dəvət mesajında verilən linkə daxil olun.
2. İştirakçı adı **(Username)** olaraq İştirakçının adı və soyadı qeyd olunmalıdır.
3. Şifrənizi **(Password)** təyin edin və Şifrəni təsdiq edin **(Confirm)**.
4. Şifrəni yeniləyin **(Update Password)** butonuna klikləyərək hesabı aktivləşdirin.

## 1.2. Məlumat idarəetmə sisteminə daxil olmaq

1. Açıq məlumatlar portalının Məlumat idarəetmə sistemində Daxil ol **(Log in)** butonuna klikləyin.
2. Istifadəçi adı **(Username)** və ya elektron poçt **(e-mail)** və şifrə **(password)** daxil edin.
3. Daxil olun **(Login)** butonuna klikləyib daxil olun.

## 1.3. Məlumat dəstlərinin idarə edilməsi

Məlumat dəstləri həmin məlumat dəstini əlavə edən Təşkilat tərəfindən idarə olunur. Sadəcə Kateqoriyalara əlavə edilməsi İRİA tərəfindən idarə edilir. Bu səbəblə iştirakçılar bu Kateqoriyalar bölməsində hər hansı bir **əməliyyat aparmamalıdır.**

### 1.3.1 Məlumat dəstinin əlavə edilməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəstləri **(Datasets)** bölməsinə klikləyin.
3. Yeni Məlumat dəsti əlavə edin.
4. Məlumat dəsti əlavə et **(Add Dataset)** düyməsini seçin.
5. Aşağıda verilmiş cədvəl əsasında Məlumat dəsti məlumatlarını daxil edin.

| **Metaməlumat**<br><br>**(İngiliscə)** | **Metaməlumat**<br><br>**(Azərbaycanca)** | **Açıqlaması** |
| --- | --- | --- |
| AZ, EN, RU Title | Azərbaycan, İngilis və Rus dilində başlıq | Məlumat dəstinə aid təsviri bir başlıq. |
| AZ, EN, RU Description | Azərbaycan, İngilis və Rus dilində təsviri (açıqlaması) | Məlumat dəsti haqqında faydalı qeydlər.<br><br>Description hissəsində məlumatın **yenilənmə tezliyi (**əsas anlayışlar bölməsində terminin izahı verilmişdir) haqqında məlumat vermək vacibdir. |
| Tags | Etiketlər | Tag, məlumat dəstini təsvir etmək və axtarışı asanlaşdırmaq üçün istifadə olunan açar sözlərdir.<br><br>(məsələn, təhsil, xərclər). |
| License | Lisenziya | Lisenziya iştirakçılara həmin məlumat dəstinin istifadəsi, paylaşılması və yenidən işlənməsi ilə bağlı hüquq və məhdudiyyətləri bildirir. Lisenziyalar və onların növləri barəsində 1.3.1.3 bölməsindən tanış ola bilərsiniz. |
| Organization | Təşkilat | Məlumat dəstini idarə edən təşkilat. |
| Visibility | Görünürlük | Görünürlük hissəsində iki seçim vardır.  <br>**Private**: yanlız məlumat idarəetmə sistemində məlumat dəsti əlçatan olur.<br><br>**Public**: Məlumat dəsti həmçinin “Açıq məlumatlar” portalında iştirakçılar tərəfindəndə əlçatan olur. |
| Source | Mənbə | Əgər paylaşılan məlumat dəsti Məlumatı açıqlayan Təşkilatın saytında yer alırsa, burada həmin link yerləşdirilə bilər. |
| Version | Versiya | Məlumat dəstinin cari versiyası. Versiyalandırma məntiqi ilə 1.3.1.2 bölməsindən tanış ola bilərsiniz. |
| AZ, EN, RU Author | Azərbaycan, İngilis və Rus dilində müəllifin adı | Məlumatların istehsalına cavabdeh olan şəxsin və ya təşkilatın adı. |
| Author Email | Müəllifin e-poçtu | Məlumatların istehsalına cavabdeh olan şəxsin və ya təşkilatın elektron poçt ünvanı. |
| AZ, EN, RU Maintainer | Azərbaycan, İngilis və Rus dilində Maintainerin adı | Lazım gələrsə, məlumatlara cavabdeh olan ikinci şəxs |
| Maintainer Email | Maintainerin e-poçtu | Məlumat dəstinə cavabdeh şəxslə əlaqə üçün e-poçt ünvanı. |

Cədvəl 1

1. Məlumat əlavə et **(Add Data)** düyməsinə klikləyərək məlumat yükləmə səhifəsinə keçin.
2. Aşağıda verilmiş cədvəl əsasında məlumatlarınızı daxil edin.

| **Metaməlumat**<br><br>**(İngiliscə)** | **Metaməlumat**<br><br>**(Azərbaycanca)** | **Açıqlaması** |
| --- | --- | --- |
| Data | Məlumat | Siz məlumat dəstinin resurslarını (mənbələrini) təyin edirsiniz.  <br>**Upload** və **Link** şəkilində iki seçim verilir.<br><br>**Upload**: komputerdə yer alan fayllarınız arasında seçim edirsiniz.<br><br>**Link:** API linki şəkilində saxladığınız məlumatların linkini daxil edə bilərsiniz. |
| AZ, EN, RU Name | Azərbaycan, İngilis və Rus dilində ad | Resursun təsviri adı |
| AZ, EN, RU Description | Azərbaycan, İngilis və Rus dilində açıqlama | Resurs haqqında məlumat. |
| Format | Format | Əlavə edilən mənbənin formatı qeyd olunur (CSV, JSON, XML və.s) |

Cədvəl 2

1. Məlumatları yenidən nəzərdən keçirin və bitir **(Finish)** və ya yadda saxla və yenisini əlavə et **(Save & add another)**düyməsini basaraq əməliyyatı tamamlayın.

#### 1.3.1.1. Yeni Məlumat dəsti əlavə edərkən Create Dataset və Add Data bölmələrində yer alan Title/Description fərqi

_Create Dataset bölməsində olan title və description, Məlumat dəstinin ümumi adını və təsvirini əhatə edir._

_Add Data bölməsində isə hər bir əlavə edilən data file üçün ayrıca title və description təyin edilir. Bu, fərqli data fayllarının bir Məlumat dəsti daxilində ayırd edilməsini təmin edir. Bunun əsas səbəbi, bir Məlumat dəsti daxilində bir neçə data faylının ola bilməsidir. Hər bir fayl fərqli məlumatları əhatə edə bilər._

#### 1.3.1.2. Məlumat idarəetmə sistemində yer alan məlumat dəstlərinin versiyalandırması məntiqi

İştiakçılar təqdim etdikləri Məlumat dəstlərdə baş verən hər bir dəyişiklik növünü Məlumat dəstinin məzmununa və təsirinə görə **PATCH**, **MINOR**, və ya **MAJOR** versiyalandırma altında təsnif edilir.

**PATCH** dəyişikliklər Məlumat dəstində və ya Meta məlumatda **kiçik səhvlərin düzəldilməsi** üçün istifadə olunur. Məlumat dəstinin strukturu və əsas məzmunu dəyişməz qalır, bu da iştirakçıların Məlumat dəstindən istifadə alışqanlıqlarına təsir etmir.

Nümunə:  

- "Yaş" sütununda 25 - ci sətirdəki məlumat düzəldilir  28 → 27. Versiya: 2.0.0 → 2.0.1

**MINOR** dəyişikliklər Məlumat dəstinə **yeni məlumat sütunu, mənbəsi əlavə etmək** **və ya böyük həcmdə məlumat sətirlərinin silinməsi, dəyişdirlməsi, əlavə edilməsi** zamanı istifadə olunur. Bu dəyişikliklər mövcud strukturu pozmur, yəni uyğunluq qorunur.  

Nümunə:  

- "Ünvan" sütunu əlavə edilir. Versiya: 2.0.0 → 2.1.0
- Təhsil xərcləri Məlumat dəstinə 2024 cü il üzrə olan məlumatlar əlavə edilir Versiya: 2.1.0 → 2.2.0

**MAJOR** dəyişikliklər Məlumat dəstinin **strukturuna təsir edən dəyişiklikləri** ifadə edir. Bu dəyişikliklərə Məlumat dəstinin bir sütunun silinməsi, formatının dəyişdiriməsi aid edilirki, bu da iştirakçıların Məlumat dəstindən istifadə alışqanlıqlarına ciddi təsir göstərə bilər.

Nümunə:

- "Şəhər" sütunu silinir, yerinə "Bölgə" sütunu əlavə edilir. Versiya: 2.0.0 → 3.0.0
- Telefon nömrələri tam olaraq "+994" kodu ilə təqdim edilir. Versiya: 3.0.0 → 4.0.0

#### 1.3.1.3. Məlumat idarəetmə sistemində yer alan məlumat dəstlərinə tətbiq oluna biləcək lisenziyalar

**1\. Creative Commons Attribution 4.0 International (CC BY 4.0) lisenziyası**

Bu lisenziya müəllif hüquqları ilə qorunan məzmunların, o cümlədən məlumat dəstlərinin sərbəst istifadəsinə imkan yaradır və aşağıdakı şərtləri müəyyən edir:

- **İstinad mütləqdir** – Məlumatdan istifadə edərkən müəllif(lər)ə istinad verilməlidir. Lisenziya mətninə və ya ona keçid göstərilməlidir.
- **Dəyişikliklər qeydə alınmalıdır** – Əgər məlumat dəstinə əlavə, çıxarış və ya başqa dəyişikliklər edilərsə, bu, açıq şəkildə bildirilməlidir. Müəllifin rəsmi təsdiqi kimi təqdim etmək olmaz.
- **Sərbəst istifadə və paylaşım** – Məlumatı kommersiya məqsədilə də daxil olmaqla, istənilən məqsədlə istifadə və paylaşmaq olar.
- **Uyğunlaşdırma və modifikasiya mümkündür** – Məlumat dəsti redaktə edilə, başqa mənbələrlə birləşdirilə və yeni məlumat dəsti yaradıla bilər, amma müəllifə istinad şərtdir.
- **Texniki dəyişikliklərə icazə verilir** – Məlumat istənilən formata çevrilə bilər (CSV, SQL, JSON və s.), eləcə də müxtəlif proqramlarda istifadəsi mümkündür.
- **Digər şərtləri ilə burden tanış ola bilərsiniz**: [Legal Code - Attribution 4.0 International - Creative Commons](https://creativecommons.org/licenses/by/4.0/legalcode)

**2\. Creative Commons Zero (CC0) lisenziyası**

- Məzmuna dair bütün hüquqlardan imtina edildiyini və onun ictimai mülkiyyətə verildiyini ifadə edir. Məzmundan istənilən məqsədlə, məhdudiyyətsiz və istinadsız istifadə etmək mümkündür.

### 1.3.2. Mövcud Məlumat dəstinə düzəliş edilməsi

#### 1.3.2.1. Mövcud Məlumat dəstinin metaməlumatlarına düzəliş edilməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəsti **(Datasets)** bölməsinə klikləyin.
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.
4. Metaməlumatları redaktə et **(Edit Metadata)** bölməsini seçin.
5. Dəyişmək istədiyiniz məlumatları **cədvəl 1** əsasında yeniləyin.
6. Bütün yenilikləri nəzərdən keçirin və dəyişiklikləri tətbiq etmək üçün Yadda saxla **(Save)** düyməsini basın.

#### 1.3.2.2. Mövcud Məlumat dəstini silmək

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəsti **(Datasets)** bölməsinə klikləyin.
3. Məlumat dəstiin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.
4. Silmək **(Delete)** düyməsini seçin: Təsdiq dialoq pəncərəsini göstərəcək.
5. Təsdiq et **(Confirm)** düyməsini basaraq Məlumat dəstii silmə prosesini tamamlayın.

### 1.3.3. Mövcud məlumat dəstinin resurslarının idarə olunması

#### 1.3.3.1.Mövcud Məlumat dəstinə yeni resurs əlavə etmək

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəsti **(Datasets)** bölməsinə klikləyin.
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.
4. Resurlar **(Resources)** bölməsinə keçin.
5. Yeni resurs əlavə et **(Add new resource)** düyməsini basın.
6. Yeni resursun məlumatlarını **cədvəl 2** əsasında əlavə edin.
7. Məlumatları yenidən nəzərdən keçirin və Əlavə et **(Add)** və ya Yadda saxla və yenisini əlavə et **(Save & add another)** düyməsini basaraq yayımlayın.

#### 1.3.3.2 Mövcud Məlumat dəstinin resurs məlumatlarına düzəliş edilməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəsti **(Datasets)** bölməsinə klikləyin.
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.
4. Resurslar **(Resources)** bölməsini seçin.
5. Redaktə etmək istədiyiniz mövcud resursları **cədvəl 2** əsasında dəyişdirin.
6. Yenilənmələri nəzərdən keçirin və tətbiq etmək üçün Resursları yenilə **(Update Resources)** düyməsini basın.

#### 13.3.3. Məlumat dəstində mövcud resurs (məlumat faylını) silmək

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəsti **(Datasets)** bölməsinə klikləyin.
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.
4. Resurslar **(Resources)** bölməsini seçin.
5. Silmək istədiyiniz mövcud resursu seçin.
6. Silmək **(Delete)** düyməsini seçin: dialoq pəncərəsini göstərəcək.
7. Təsdiq et **(Confirm)** düyməsini basaraq Məlumat dəstini silmə prosesini tamamlayın.

### 1.3.4. Mövcud Məlumat dəstinin əməkdaşların (Collaborators) idarə olunması

#### 1.3.4.1. Mövcud Məlumat dəstinin əməkdaşların əlavə edilməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəsti **(Datasets)** bölməsinə klikləyin.
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarət et **(Manage)** düyməsinə klikləyin.
4. Əməkdaşlar **(Collaborators)** bölməsini seçin.
5. Əməkdaşlar əlavə et **(Add Collaborators)** butonuna klikləyin.
6. Axtarış hissəsinə iştirakçı adını daxil edərək əməkdaş kimi təyin etmək istədiyiniz iştirakçını seçin.
7. Role bölməsindən member, editor və admin arasından uyğun rolu seçin (anlayışlar bölməsindən rollar haqqında məlumt əldə edə bilərsiniz).
8. Əməkdaş əlavə et **(Add Collaborator)** butonuna klikləyərək yeni əməkdaşınızı əlavə edin.

#### 1.3.4.2. Mövcud Məlumat dəstinin əməkdaşların rollarının dəyişdirilməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəsti **(Datasets)** bölməsinə klikləyin.
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarət et **(Manage)** düyməsinə klikləyin.
4. Əməkdaşlar **(Collaborators)** bölməsini seçin.
5. Rolunu dəyişmək istədiyiniz iştirakçının açar butonuna klikləyin.
6. Rolunu uyğun olaraq Admin, Editor, Member’ə dəyişdirdikdən sonra əməkdaşı yeniləyin **(Update Collaborator)** butonuna klikləyərək prosesi tamamlayaq.

#### 1.3.4.3. Mövcud Məlumat dəstinin əməkdaşların silinməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Məlumat dəsti **(Datasets)** bölməsinə klikləyin.
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarət et **(Manage)** düyməsinə klikləyin.
4. Əməkdaşlar **(Collaborators)** bölməsini seçin.
5. Silmək istədiyiniz iştirakçının qarşısındakı **X** butonuna klikləyin.
6. Açılan dialoq qutusunda Təsdiq et **(Confirm)** butonuna klikləyərək prosesi tamamlayın.

## 1.4. Mövcud Təşkilatı (Oganization) idarə edilməsi

#### 1.4.1. Yeni təşkilatın yaradılması

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Təşkilatlar **(Organizations)** bölməsinə klikləyin.
3. Təşkilat əlavə et **(Add Organization)** butonuna klikləyin.
4. Açılan səhifədə lazım olan sahələri aşağıdakı cədvəl əsasında doldurun.

| **Metaməlumat**<br><br>**(İngiliscə)** | **Metaməlumat**<br><br>**(Azərbaycanca)** | **Açıqlaması** |
| --- | --- | --- |
| Title | Başlıq | Təşkilatın adı |
| Description | Açıqlama | Təşkilat haqqında məlumat |
| Image | Şəkil | Təşkilatın şəkil və ya logosu. 43 x 43 piksel ölçüsündə olması məqsədə uyğundur. |

Cədvəl 3

1. Məlumatları nəzərdən keçirin və təşkilatı yaradın **(Create Organization)** butonuna klikləyərək prosesi tamamlayın.

#### 1.4.2. Təşkilat məlumatlarının redaktə edilməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Təşkilatlar **(Organizations)** bölməsinə klikləyin.
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.
4. Lazım olan sahələri **cədvəl 3** əsasında dəyişdirin.
5. Yeniləmələrinizi nəzərdən keçirin və dəyişiklikləri saxlamaq üçün Təşkilatı yeniləyin **(Update Organization)** düyməsinə klikləyin.

#### 1.4.2. Mövcud təşkilatın silinməsi

Mövcud təşkilatı əgər içində heç bir məlumat dəsti mövcud deyilsə aşağıdakı addımları izləyərək silmək mümkündür, əks halda silinmə prosesi mümkün olmayacaq.

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Təşkilatlar **(Organizations)** bölməsinə klikləyin.
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.
4. Silmək **(Delete)** butonuna basin.
5. Açılan dialoq pəncərəsində Təsdiq edirəm **(Confirm)** butonuna basaraq prosesi tamamlayın.

#### 1.4.3 Mövcud Təşkilata yeni member (üzv) əlavə etmək.

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Təşkilat Bölməsinə Keçid: Əsas naviqasiya panelində Təşkilatlar **(Organizations)** bölməsinə klikləyin.  
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.  
4. Üzvlər **(Members)** bölməsini seçin.
5. Üzv əlavə et **(Add Member)** butonuna klikləyin.
6. Təşkilata əlavə etmək üçün Yeni iştirakçı **(New user)** hissəsini iştirakçının mailini və uyğun rolunu (Admin, Editor, Member) təyin edin.
7. Üzv əlavə et **(Add Member)** butonuna klikləyərək yeni iştirakçını mövcud təşkilata dəvət edin.

#### 1.4.4 Mövcud Təşkilatdakı memberləri (üzvləri) rollarını dəyişmək.

##### Üsul 1

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Təşkilatlar **(Organizations)** bölməsinə klikləyin.  
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.  
4. Üzvlər **(Members)** bölməsini seçin.
5. Rolunu dəyişmək istədiyiniz iştirakçının qarşısında olan açar butonuna klikləyin.
6. Rolunu uyğun olaraq Admin, Editor, Member’ə dəyişdirdikdən sonra Üzvü yeniləyin **(Update Member)** butonuna klikləyək prosesi tamamlayın.

##### Üsul 2

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Əsas naviqasiya panelində Təşkilatlar **(Organizations)** bölməsinə klikləyin.  
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.  
4. Üzvlər **(Members)** bölməsini seçin.
5. Üzv əlavə et **(Add Member)** butonuna klikləyin.
6. Mövcud iştirakçı **(Existing user)** hissəsindən iştirakçı adını tapıb rolunu (Admin, Editor, Member) olaraq dəyişdirin.olaraq dəyişdirin.
7. Üzv əlavə et **(Add Member)** butonuna klikləyərək iştirakçının rolunu dəyişin.

#### 1.4.5 Mövcud Təşkilatdakı memberləri (üzvləri) silmək.

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. İdarəetmə sisteminə girişƏsas naviqasiya panelində Təşkilatlar **(Organizations)** bölməsinə klikləyin.  
3. Məlumat dəstinin idarəetmə interfeysinə keçmək üçün İdarə et **(Manage)** düyməsinə klikləyin.  
4. Üzvlər **(Members)** bölməsini seçin.
5. Silmək istədiyiniz iştirakçının sağ tərəfində olan **X** butonuna klikləyin.
6. Açılan Dialoq pəncərəsində Təsdiq et **(Confirm)** butonuna klikləyərək silmə prosesini tamamlayın.

## 1.5. İştirakçı hesabının idarə edilməsi

“Açıq məlumatlar” portalında Məlumat dəstinə daxil olduğumuz zaman fəaliyyət axını bölməsi mövcuddur, bu bölmədə məlumat dəsti üzəridə edilən yeniləmələri dair xronoloji ardıcıllıq və həmçinində yeniləməni edən **İştirakçının adı** portal istifadəçilərinə görünür. Bu səbəblə **İştirakçı adı və digər məlumatlar düzgün** qeyd olunmalıdır.

#### 1.5.1. İştirakçı Profilinin məlumatlarının redaktə edilməsi.

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Profil parametrləri **(Profile Settings)** bölməsinə keçid edin.
3. Aşağıda verdiyim cədvəldəki məlumatları zəhmət əlavə edə və ya dəyişdirə bilərsiniz.

| **Data** | **Məlumat** | **Açıqlaması** |
| --- | --- | --- |
| Full name | Ad, Soyad | İştrakçının tam adı yazılmalıdır. |
| Email | E-poçt | Iştirakçının Elektron poşt ünvanı yerləşir. |
| About | Haqqında | İştirakçı özü haqqında məlumat yerləşdirə bilər. |
| Profile picture | Profil şəkli | İştirakçı öz şəkilini bura yerləşdirə bilər. |

Cədvəl 4

1. Profili yeniləyin **(Update Profile)** hissəsinə klik edərək İştirakçı profilinin redaktəsini tamamlaya bilərik.

#### 1.5.2. İştirakçı Profilinin şifrəsinin dəyişdirilməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Profil parametrləri **(Profile Settings)** bölməsinə keçid edin.
3. **Old Password** hissəsinə cari şifrənizi yazın.
4. **Pasword** və **Confirm Password** hissəsinə yeni şifrənizi yazın.
5. Profili yeniləyin **(Update Profile)** hissəsinə klik edərək İştirakçı profilinin şifrə yeniləmə prosesini tamamlayın.

## 1.6. Portalın API vasitəsilə istifadəsi

### 1.6.1 API açarının yaradılması

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Profilinizə (İştirakçı adınızın yazıldığı hissə) klikləyin.
3. API açarlar **(API Tokens)** bölməsinə keçid edin.
4. Ad **(Name)** hissəsində API açarınızın adını yazın.
5. API açarı yarat **(Create API Token)** butonuna basaraq API açarınızı yaratma prosesini tamamlayın.

Bu API açarından istifadə edərək məlumat dəstlərini yükləmək üçün aşağıdakı fayllardan istifadə edə bilərsiniz.

<https://docs.ckan.org/en/2.10/maintaining/filestore.html?highlight=resource_create#filestore-api>

[API guide — CKAN 2.10.7 documentation](https://docs.ckan.org/en/2.10/api/index.html)

### 1.6.2. API açarının silinməsi

1. Açıq məlumatlar portalının Məlumat idarəetmə sisteminə giriş edin.
2. Profilinizə (İştirakçı adınızın yazıldığı hissə) klikləyin.
3. API açarlar **(API Tokens)** bölməsinə keçid edin.
4. Silmək istədiyiniz tokeni **X** butonuna basaraq silə bilərsiniz.

### 1.6.3 API vasitəsi ilə məlumat dəstlərinin əlavə edilməsi

**1\. Məlumat idarəetmə sistemində API-ə qoşulma və faylları ehtiva edən mənbə qovluq.**

&nbsp;

&nbsp;

\# CKAN instance main URL
ckan_url = "<http://opendata-api.idda.az/api/3/action>"

\# Package create – for creating dataset itself (without files, which later can contain any number of # files):
resource_create_url = ckan_url + "/resource_create"

\# Resource create – for adding specific file with data into already created CKAN dataset:
package_create_url = ckan_url + "/package_create"

\# Title translations are optional
trns_en = GoogleTranslator(source='az', target='en')
trns_ru = GoogleTranslator(source='az', target='ru')

\# API key is unique for each publisher organization and generated/shared by CKAN Admin. Below is just an example
api_key = ("eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJqdGkiOiJmN2ExYmMyY2QzZTRlNWY2YTZiN2M4ZDllMGYxYTIiLCJpYXQiOjE3MzM5MTI0MDF9.jgbfdY76kkk")

\# Defining that authorisation is made by API key
headers = {"Authorization": api_key}

\# Your directory where required dataset files are located:
dir_path = '&lt;/your_directory_where_files_located&gt;'

&nbsp;

&nbsp;

&nbsp;

**2\. Məlumat dəstində Metaməlumatların doldurulması üçün element adları.**

&nbsp;

package_data = {
    "\_csrf_token": "IjA1ODU0MmU2MGZjYmI4MmFjOTIxOTI0YzAxYzE3NGExYzBmYzU1ZDIi.Z1lN-A.t9BcCBwgWm1hSubcD_4SVO182uo",
    "name": dataset_name,
    "title_translated-az": dataset_title, # title in Azerbaijani
    "title_translated-en": title_en, # title in English
    "title_translated-ru": title_ru, # title in Russian
    "url": dataset_name,  # Easy practice to generate URL is using dataset name
    "owner_org": '9b44b52f-2116-48c8-9565-d9dc026dca8f',   # This ID is unique for each publisher  

&nbsp;# organization and share by CKAN admin
    "license_id": 'notspecified',
    "private": False, # if set False, it will be publicly available in portal
    "tag_string": directory_name  # Easy practice to generate TAG is using directory name
    }

**3**. **Məlumat dəstində konkret faylın metaməlumatlarının doldurulması üçün element adları**.

&nbsp;       # Get the package ID from the response. Package is created code above, before resource.

&nbsp;       package_id = package_response.json()\["result"\]\["id"\]

&nbsp;       # Parameters for the resource

&nbsp;       resource_data = {

&nbsp;           "package_id": package_id,

&nbsp;           "name": resource_name, # name of the file

&nbsp;           "format": 'CSV', # as your file extensions (csv, json,etc)

&nbsp;           "name_translated-az": resource_name,

&nbsp;           "name_translated-en":title_en, # name of the file in English

&nbsp;           "name_translated-ru":title_ru # name of the file in Russian

&nbsp;

&nbsp;       }  

&nbsp;

&nbsp;
