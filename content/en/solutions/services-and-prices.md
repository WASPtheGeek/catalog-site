---
title: "Service Pricing"
description: "We offer a transparent and fixed price list for the maintenance, repair, and registration of cash registers and POS systems."
layout: "services-prices"

prices_section:
  enable: true
  subtitle: "Price List"
  title: "Technical Support and Service Costs"
  note: "*All prices are in EUR excluding 21% VAT."
  
  # Service agreement modules (pricing plans)
  plans:
    - name: "Economy Agreement"
      price: "96.00"
      period: "per year"
      badge: "Popular Choice"
      features:
        - text: "Repair or maintenance on business days (09:00-18:00):"
          value: "35.00€/hr."
        - text: "Repair or maintenance on evenings/mornings (18:00-22:00 / 06:00-09:00):"
          value: "50.00€/hr."
        - text: "Repair or maintenance on weekends and holidays:"
          value: "65.00€/hr."
        - text: "Phone consultation (up to 20 min.):"
          value: "10.00€"
        - text: "Remote IT support (up to 20 min.):"
          value: "10.00€"
        
    - name: "Standard Agreement"
      price: "192.00"
      period: "per year"
      badge: "Full-Service Support"
      features:
        - text: "Phone consultations during business hours (09:00-18:00):"
          value: "FREE"
          free: true # Added flag for a free service
        - text: "Remote IT support during business hours (09:00-18:00):"
          value: "FREE"
          free: true
        - text: "Repair or maintenance on business days (09:00-18:00):"
          value: "35.00€/hr."
        - text: "Repair or maintenance on evenings/mornings (18:00-22:00 / 06:00-09:00):"
          value: "50.00€/hr."
        - text: "Repair or maintenance on weekends and holidays:"
          value: "65.00€/hr."
        - text: "Consultation / remote support outside business hours (20 min.):"
          value: "10.00€"

  # Standard service tables
  categories:
    - name: "Service Technician On-Site Visits"
      items:
        - service: "In Riga during business hours"
          price: "55.00"
        - service: "In Riga on weekends and holidays"
          price: "95.00"
        - service: "Outside Riga (more than 50 km)"
          price: "By agreement"

    - name: "Maintenance and Repair"
      items:
        - service: "POS system repair (1 hr.)"
          price: "55.00"
        - service: "One-time POS technical maintenance (1 hr.)"
          price: "55.00"
        - service: "Cash register system operation training (1 hr.)"
          price: "55.00"
        - service: "Programmer's work (1 hr.)"
          price: "65.00"
        - service: "Local computer network development, design, and installation"
          price: "45.00"
---