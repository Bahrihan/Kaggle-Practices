🏠 Yapısal ve Genel Bilgiler
MSSubClass
Ev tipini tanımlar. Sayısal gibi görünür ama aslında kategoriktir. Örn. “1 katlı yeni ev”, “2 katlı PUD”, “Dublex” gibi.

MSZoning
Evin bulunduğu alanın imar sınıfı. Yani hangi amaçla kullanılabileceği (konut, ticaret, tarım vb.).

LotFrontage
Arsanın yola bakan cephesinin uzunluğu (feet cinsinden).

LotArea
Arsanın toplam alanı (square feet).

Street
Arsanın bağlı olduğu yolun türü (asfalt mı çakıl mı).

Alley
Arka giriş yolu olup olmadığını belirtir.

LotShape
Arsanın geometrik şekli: düzgün dikdörtgen mi, düzensiz mi?

LandContour
Arsanın düz mü eğimli mi olduğunu tanımlar.

Utilities
Arsa için mevcut olan altyapı hizmetleri (elektrik, su, kanalizasyon vb.)

LotConfig
Arsanın yerleşim şekli (iç sokakta mı, köşe parsel mi, çıkmaz sokakta mı vb.).

LandSlope
Arsanın eğim miktarı (hafif mi, orta mı, dik mi).

🏙️ Lokasyon ve Dış Faktörler
Neighborhood
Evin bulunduğu mahalle (Ames şehri içinde). Fiyat üzerinde çok etkili olabilir.

Condition1 & Condition2
Evin yakınındaki yollar, demiryolları veya parklara olan konum ilişkisi. İki farklı durum varsa Condition2 de devreye girer.

BldgType
Binanın genel tipi: müstakil ev, dubleks, apartman, sıra ev gibi.

HouseStyle
Evin kat sayısı ve iç düzeni: 1 katlı, 2 katlı, split-level, çatı katı gibi.

🏗️ İnşaat ve Yapısal Kalite
****
OverallQual
Ev yapım kalitesi (1’den 10’a kadar). Yüksekse lüks evdir.

OverallCond
Evin genel durumu (1’den 10’a). Yani bakımlı mı yıpranmış mı.

YearBuilt
Evin inşa edildiği yıl.
****
YearRemodAdd
Yenileme veya ekleme yapıldıysa o yıl. Yoksa YearBuilt ile aynıdır.

🏠 Çatı ve Dış Cephe
RoofStyle
Çatı tipi (düz, üçgen, eğimli, çift katlı vb.)

RoofMatl
Çatı malzemesi (kiremit, şıngıl, metal, ahşap vb.)

Exterior1st & Exterior2nd
Evin dış cephe kaplamasında kullanılan malzemeler. İki farklı malzeme varsa Exterior2nd kullanılır.

MasVnrType
Tuğla/taş kaplama türü (varsa).

MasVnrArea
Taş/tuğla kaplama alanı (sqft olarak).

🧱 Dış Kalite ve Temel
ExterQual
Dış cephenin kalitesi (Excellent, Good, etc.)

ExterCond
Dış cephenin durumu (Excellent, Good, etc.)

Foundation
Temel tipi (beton, taş, blok, ahşap vs.)

🧱 Bodrum (Basement) ile İlgili Değişkenler
BsmtQual
Bodrum tavan yüksekliği. (Ex = çok yüksek, Po = çok alçak)

BsmtCond
Bodrumun genel yapısal durumu. (Ex → Po)

BsmtExposure
Bodrumda dışarıya açık pencere/duvar durumu (walkout veya garden level).

BsmtFinType1
Bodrumun en büyük bitmiş alanı tipi (Yaşam alanı mı, oyun odası mı, düşük kalite mi?)

BsmtFinSF1
BsmtFinType1 için bitmiş metrekare (sqft)

BsmtFinType2
İkinci bitmiş alan türü (varsa)

BsmtFinSF2
BsmtFinType2 için bitmiş alan (sqft)

BsmtUnfSF
Bitmemiş bodrum alanı (sqft)

TotalBsmtSF
Tüm bodrum alanı (bitmiş + bitmemiş)

🌡️ Isıtma ve Elektrik
Heating
Evin ısıtma sistemi türü (gazlı, yerden, duvar tipi vs.)

HeatingQC
Isıtma sisteminin kalitesi ve durumu

CentralAir
Merkezi klima var mı? (Y/N)

Electrical
Elektrik sistemi tipi (sigorta kutusu türleri)

🏡 Yaşam Alanı ve Katlar
1stFlrSF, 2ndFlrSF
Birinci ve ikinci kat yaşam alanı (sqft)

LowQualFinSF
Düşük kaliteli bitmiş alan (genelde küçük, kullanışsız alanlar)

GrLivArea
Zemin üstündeki toplam yaşam alanı (en önemli metriklerden)

🛁 Banyo ve Yatak Odası Sayısı
BsmtFullBath, BsmtHalfBath
Bodrum katındaki tam ve yarım banyolar

FullBath, HalfBath
Zemin üzerindeki tam ve yarım banyolar

Bedroom
Zemin üzerindeki yatak odası sayısı

Kitchen
Mutfak sayısı

KitchenQual
Mutfak kalitesi (Ex, Gd, TA, Fa, Po)

🛋️ Oda ve Fonksiyonellik
TotRmsAbvGrd
Zemin üzerindeki toplam oda sayısı (banyo hariç)

Functional
Evin genel fonksiyonelliği (eksik odalar, tam çalışmayan sistemler vs.)

🔥 Şömine
Fireplaces
Şömine sayısı

FireplaceQu
Şömine kalitesi

🚗 Garaj Bilgileri
GarageType
Garaj tipi (bağımsız, entegre, bodrumda vs.)

GarageYrBlt
Garajın yapım yılı

GarageFinish
Garajın iç bitirme durumu (bitmiş, yarım, bitmemiş)

GarageCars
Garajda kaç araçlık alan var

GarageArea
Garajın metrekare olarak büyüklüğü

GarageQual, GarageCond
Garajın kalitesi ve yapısal durumu

🛣️ Park Yolu, Teras ve Diğer Açık Alanlar
PavedDrive
Giriş yolu asfalt mı?

WoodDeckSF
Ahşap teras alanı (sqft)

OpenPorchSF
Açık ön/arka veranda alanı

EnclosedPorch
Kapalı veranda alanı

3SsnPorch
3 mevsim kullanılabilir veranda alanı

ScreenPorch
Sineklikli veranda alanı

🏊 Havuz ve Diğer Özellikler
PoolArea
Havuzun büyüklüğü (sqft)

PoolQC
Havuz kalitesi

Fence
Çit türü ve kalitesi

MiscFeature
Sistemde tanımlı olmayan ekstra bir şey (örneğin: kulübe, asansör)

MiscVal
Bu ekstra özelliğin parasal değeri

🗓️ Satış Bilgileri
MoSold, YrSold
Satışın gerçekleştiği ay ve yıl

SaleType
Satış tipi (normal satış, yeni konut, aile içi, vs.)

SaleCondition
Satışın nedeni veya durumu (normal mi, mahkeme mi, takas mı, aile içi mi)