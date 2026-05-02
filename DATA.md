# 📊 KarmaPath 数据收集计划

## 数据概览

| 数据类型 | 目标数量 | 来源 | 优先级 |
|---------|---------|------|--------|
| 寺庙数据 | 670+ | Wikipedia/旅游局/众包 | ⭐⭐⭐ |
| 祈福点数据 | 3,000+ | 寺庙附属数据 | ⭐⭐⭐ |
| 吠陀占星数据 | 27 Nakshatra + 12 Rashi | 开源占星库 | ⭐⭐⭐ |
| 神话故事 | 200+ | Ramayana/Mahabharata | ⭐⭐ |
| 灵验口碑 | 用户UGC | 社区运营 | ⭐⭐ |

## 寺庙数据字段

```json
{
  "id": "TN_CHIDAMBARAM_001",
  "name": { "en": "Nataraja Temple", "ta": "நடராஜர் கோயில்", "hi": "नटराज मंदिर" },
  "type": "hindu",
  "deity": "Shiva as Nataraja",
  "state": "Tamil Nadu",
  "city": "Chidambaram",
  "location": { "lat": 11.4013, "lng": 79.7086 },
  "importance": 5,
  "UNESCO": false,
  "annual_festival": "Thiruvathirai (Dec-Jan)"
}
```

## 吠陀占星数据

### 基础数据
```
12 Rashi (星座):
1. Mesha (Aries) - मेष
2. Vrishabha (Taurus) - वृषभ
3. Mithuna (Gemini) - मिथुन
4. Karka (Cancer) - कर्क
5. Simha (Leo) - सिंह
6. Kanya (Virgo) - कन्या
7. Tula (Libra) - तुल
8. Vrishchika (Scorpio) - वृश्चिक
9. Dhanu (Sagittarius) - धन
10. Makara (Capricorn) - मकर
11. Kumbha (Aquarius) - कुंभ
12. Meena (Pisces) - मीन

27 Nakshatra (月宿):
Ashwini, Bharani, Krittika, Rohini, Mrigashira, Ardra,
Punarvasu, Pushya, Ashlesha, Magha, Purva Phalguni, Uttara Phalguni,
Hasta, Chitra, Swati, Vishakha, Anuradha, Jyeshtha,
Mula, Purva Ashadha, Uttara Ashadha, Shravana, Dhanishta, Shatabhisha,
Purva Bhadrapada, Uttara Bhadrapada, Revati

9 Graha (行星):
Sun, Moon, Mars, Mercury, Jupiter, Venus, Saturn, Rahu, Ketu
```

### 占星API
- **AstroSage API**（商业）
- **VedicRishi API**（商业）
- **Swiss Ephemeris**（开源，自建）

---

*Last updated: 2026-05-02*
