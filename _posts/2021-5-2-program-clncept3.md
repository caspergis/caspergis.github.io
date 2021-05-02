---
title: Program concept(part 3)
layout: post
---

## 1. Windows of S1. Main Section 
### 1. Start page
#### Destination:  
Like Start page on Eclipse, NetBeans or other programs.
#### Window properties:  
- PROP_CLOSING_DISABLED - false
- PROP_DRAGGING_DISABLED - true
- PROP_MAXIMIZATION_DISABLED - true
- PROP_SLIDING_DISABLED - true  
- PROP_UNDOCKING_DISABLED - true

### 2. Active map editor
#### Destination:  
The main program window where the user among others can view the content of the active map, edit layers, take measurements and add layers using the D'n'D mechanism.
#### Window properties:  
- PROP_CLOSING_DISABLED - true
- PROP_DRAGGING_DISABLED - true
- PROP_MAXIMIZATION_DISABLED - false
- PROP_SLIDING_DISABLED - true  
- PROP_UNDOCKING_DISABLED - true

### 3. MapDisplayer
#### Destination:  
Window, where user van view content of the map other than active, take measurements, się tools(can't edit Layers).
#### Window properties:  
 - PROP_CLOSING_DISABLED - false
- PROP_DRAGGING_DISABLED - false
- PROP_MAXIMIZATION_DISABLED - true
- PROP_SLIDING_DISABLED - false  
- PROP_UNDOCKING_DISABLED - false

### 4. PrintOut
#### Destination:  
Like PrintOut window on QGIS.
#### Window properties:  
 - PROP_CLOSING_DISABLED - false
- PROP_DRAGGING_DISABLED - true
- PROP_MAXIMIZATION_DISABLED - true
- PROP_SLIDING_DISABLED - true  
- PROP_UNDOCKING_DISABLED - false
