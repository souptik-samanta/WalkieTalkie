---
title: "Walkie Talkie"
author: "Souptik Samanta"
description: "homemade walkie talkie with infinite range using nrf and esp32 and also radio recive transmit for fun lol"
created_at: "2025-06-01"
--- 

---

### Total Time Taken: around 24hrs (maybe more lol)

---

## Day 1 - ~4hrs  
researched about legal freqs in india  
i kinda deep dived into docs and posts and found which ones i can actually use without going to jail lol  
measured distance from my house to my friend’s for range test (he willl be my lab test sub basically)

also ended up reading too much on illegal transmission...not gonna do that dw

---

## Day 2 - ~3hrs  
drew up the layout on paper  
listed out the features like audio tx/rx, maybe add a screen idk  
not final yet but idea is solid  
want it to work offline too like short range voice over nrf

---

## Day 3 - ~4.5hrs  
connected stuff on breadboard (esp32 + usb-c + amp + mic)  
most stuff worked  
still testing nrf lib (found a buggy one but kinda fixed it)  
trying to keep it small and powered by li-ion battery  
usb-c charging works!!

![Build Progress](./img/image.png)

---

## Day 4 - ~10hrs (or more idk)  
spent whole day researching modules for radio receive + transmit  
found a way to use it like a fm radio too  
added speaker + mic with switch  
was messy, took hours, some stuff still not stable  
but yea now it can talk + maybe listen to radio  
no clue about final box tho

![Radio Stuff](./img/image-1.png)

---

might add more features later like channel select or OLED screen... or just move to custom pcb if this one lives lol
