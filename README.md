F-INVEST Signal Engine V1.0
مشروع مستقل لتحليل عملة محددة على فريم 5 دقائق، مستوحى من العناصر الظاهرة في الفيديو.
مواصفات النسخة
Symbol محدد يدويًا، الافتراضي: BTC/USDT
Timeframe: 5m
Volume Filter: 1.3x
Volume Lookback: 11
Impulse WMA: 50 / 103
Momentum Confirmation: OFF
SL: 30
TP1: 15
TP2: 30
TP3: 50
Analysis only: لا يرسل أوامر تداول.
تشغيل
pip install -r requirements.txt
python main.py
لتغيير العملة:
SYMBOL=ETH/USDT python main.py
