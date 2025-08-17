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

