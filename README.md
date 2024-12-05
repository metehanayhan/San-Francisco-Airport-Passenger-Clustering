[EN]

# San Francisco Airport Passenger Clustering

## About the Project
This project uses passenger movement data from San Francisco International Airport to perform K-Means clustering and create meaningful passenger segments. The goal is to understand different passenger behaviors at the airport and gain insights into various passenger groups. The Elbow Method is employed to determine the optimal number of clusters, and the results are visualized to highlight the segmentation.

## Dataset Overview
The dataset used in this project includes the following features related to passenger movements:
- **Activity Period**: The year and month of the activity.
- **Operating Airline**: The airline operating the flight.
- **Operating Airline IATA Code**: IATA code of the operating airline.
- **Published Airline**: The airline that published the flight.
- **Published Airline IATA Code**: IATA code of the published airline.
- **GEO Summary**: Geographic summary of the flight.
- **GEO Region**: Geographic region or country of the flight.
- **Activity Type Code**: Type of passenger activity (e.g., Enplaned, Deplaned).
- **Price Category Code**: Price category of the ticket.
- **Terminal**: The terminal from which passengers are served.
- **Boarding Area**: The area or gate where passengers board the plane.
- **Passenger Count**: The number of passengers in the specified activity.

## Steps
1. **Exploratory Data Analysis (EDA)**: Initial analysis of the dataset, including null value handling and summary statistics.
2. **Data Preprocessing**: Filling missing values, encoding categorical variables, and scaling features.
3. **K-Means Clustering**: Using K-Means to cluster the data.
4. **Elbow Method**: Determining the optimal number of clusters.
5. **Clustering Results**: Analyzing and visualizing the clusters based on passenger count and geographic region.

## Requirements
The project requires the following Python libraries:
- pandas
- scikit-learn
- matplotlib
- yellowbrick
- scipy

## Results
The optimal number of clusters was determined using the Elbow Method. The silhouette score achieved was 0.828, indicating well-defined clusters. The results are visualized to show the relationship between passenger count and geographical region across different clusters.

[TR]

# San Francisco Airport Passenger Clustering

## Proje Hakkında
Bu proje, San Francisco Uluslararası Havalimanı'ndan alınan yolcu hareket verilerini kullanarak K-Means clustering yöntemiyle anlamlı yolcu segmentleri oluşturmayı amaçlamaktadır. Havalimanındaki farklı yolcu davranışlarını anlamak ve çeşitli yolcu grupları hakkında içgörüler elde etmek hedeflenmiştir. Optimum küme sayısını belirlemek için Elbow Method kullanılmış ve segmentasyon sonuçları görselleştirilmiştir.

---

## Veri Seti Özeti
Projede kullanılan veri seti, yolcu hareketleriyle ilgili şu özellikleri içermektedir:
- **Activity Period**: Hareketin gerçekleştiği yıl ve ay.
- **Operating Airline**: Uçağı işleten havayolu şirketi.
- **Operating Airline IATA Code**: İşleten havayolunun IATA kodu.
- **Published Airline**: Uçuşu yayımlayan havayolu şirketi.
- **Published Airline IATA Code**: Yayımlayan havayolunun IATA kodu.
- **GEO Summary**: Uçuşun coğrafi özeti.
- **GEO Region**: Uçuşun coğrafi bölgesi veya ülkesi.
- **Activity Type Code**: Yolcu hareket türü (örn. Biniş, İniş).
- **Price Category Code**: Biletin fiyat kategorisi.
- **Terminal**: Yolcuların hizmet aldığı terminal.
- **Boarding Area**: Yolcuların uçağa bindiği alan veya kapı.
- **Passenger Count**: Belirtilen hareket türündeki yolcu sayısı.

---

## Adımlar
1. **Exploratory Data Analysis (EDA)**: Veri setinin ilk analizi, eksik değerlerin kontrolü ve özet istatistiklerin çıkarılması.
2. **Data Preprocessing**: Eksik değerlerin doldurulması, kategorik değişkenlerin kodlanması ve özelliklerin ölçeklendirilmesi.
3. **K-Means Clustering**: Veriler üzerinde K-Means yöntemiyle kümeleme yapılması.
4. **Elbow Method**: Optimum küme sayısının belirlenmesi.
5. **Clustering Results**: Yolcu sayısı ve coğrafi bölgeye dayalı kümelerin analiz edilmesi ve görselleştirilmesi.

---

## Gereksinimler
Bu projeyi çalıştırmak için aşağıdaki Python kütüphaneleri gereklidir:
- pandas
- scikit-learn
- matplotlib
- yellowbrick
- scipy


## Sonuçlar
- **Elbow Method** ile optimum küme sayısı belirlendi.
- **Silhouette Skoru**: 0.828, kümelerin iyi tanımlandığını göstermektedir.
- **Kümeleme Sonuçları**: Yolcu sayısı ve coğrafi bölge arasındaki ilişki, farklı kümelerle görselleştirilerek analiz edilmiştir. Bu analizler, havalimanındaki farklı yolcu gruplarının davranışlarını anlamak için güçlü görüler sunmaktadır.
