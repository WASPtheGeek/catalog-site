---
title: "Pakalpojumu cenas"
description: "Piedāvājam caurspīdīgu un fiksētu cenrādi kases aparātu un POS sistēmu apkalpošanai, remontam un reģistrācijai."
layout: "services-prices"

prices_section:
  enable: true
  subtitle: "Cenrādis"
  title: "Tehniskā atbalsta un servisa pakalpojumu izmaksas"
  note: "*Visas cenas norādītas EUR bez PVN 21%."
  
  # Apkalpošanas līgumu moduļi (tarifu plāni)
  plans:
    - name: "Ekonomiskais līgums"
      price: "96.00"
      period: "gadā"
      badge: "Populāra izvēle"
      features:
        - text: "Remonts vai apkalpošana darba dienās (09:00-18:00):"
          value: "35.00€/st."
        - text: "Remonts vai apkalpošana vakaros/rītos (18:00-22:00 / 06:00-09:00):"
          value: "50.00€/st."
        - text: "Remonts vai apkalpošana brīvdienās un svētku dienās:"
          value: "65.00€/st."
        - text: "Konsultācija pa tālruni (līdz 20 min.):"
          value: "10.00€"
        - text: "Attālinātais IT atbalsts (līdz 20 min.):"
          value: "10.00€"
        
    - name: "Standarta līgums"
      price: "192.00"
      period: "gadā"
      badge: "Pilna servisa atbalsts"
      features:
        - text: "Konsultācijas pa tālruni darba laikā (09:00-18:00):"
          value: "BEZMAKSAS"
          free: true # Добавили флаг для бесплатной услуги
        - text: "Attālinātais IT atbalsts darba laikā (09:00-18:00):"
          value: "BEZMAKSAS"
          free: true
        - text: "Remonts vai apkalpošana darba dienās (09:00-18:00):"
          value: "35.00€/st."
        - text: "Remonts vai apkalpošana vakaros/rītos (18:00-22:00 / 06:00-09:00):"
          value: "50.00€/st."
        - text: "Remonts vai apkalpošana brīvdienās un svētku dienās:"
          value: "65.00€/st."
        - text: "Konsultācija / attālinātais atbalsts ārpus darba laika (20 min.):"
          value: "10.00€"

  # Standarta pakalpojumu tabulas
  categories:
    - name: "Servisa meistara izsaukumi"
      items:
        - service: "Rīgā darba laikā"
          price: "55.00"
        - service: "Rīgā brīvdienās un svētku dienās"
          price: "95.00"
        - service: "Ārpus Rīgas (vairāk nekā 50 km)"
          price: "Pēc vienošanās"

    - name: "Apkalpošana un remonts"
      items:
        - service: "POS sistēmas remonts (1 st.)"
          price: "55.00"
        - service: "POS vienreizējā tehniskā apkope (1 st.)"
          price: "55.00"
        - service: "Apmācība darbam ar kases sistēmu (1 st.)"
          price: "55.00"
        - service: "Programmētāja darbs (1 st.)"
          price: "65.00"
        - service: "Lokālā datortīkla izstrāde, projektēšana un montāža"
          price: "45.00"
---