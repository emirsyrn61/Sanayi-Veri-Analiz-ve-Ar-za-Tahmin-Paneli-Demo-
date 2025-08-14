Sanayi Veri Analiz ve Arıza Tahmin Paneli 
**İçerik**:
- Flask dashboard (basit, çalışır durumda) - `app.py`
- Veri simülasyonu - `data_simulator.py`
- Model eğitimi ve kaydetme - `train_model.py`
- Örnek veri - `data/sample_sensor_data.csv`
- Otomatik PDF rapor oluşturma - `report_generator.py`
- Gereksinimler - `requirements.txt`

**Nasıl çalıştırılır (lokalde)**:
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python train_model.py      # örnek veri ile modeli eğitir ve kaydeder
python app.py              # Flask dashboard'u başlatır; http://127.0.0.1:5000
```

**Projeyi neden eklemelisiniz (LinkedIn açıklaması için hazır cümle)**:
Bu proje, üretim hattı sensörlerinden gelen verilerle arıza tahmini yapar, bakım zamanlarını önerir ve haftalık PDF raporları otomatik olarak üretir. Yünsa gibi sanayi firmalarında uygulanabilir bir prototip sunar.

---
Otomatik oluşturulmuş demo — doğrudan GitHub'a yüklemeye uygun. 
