# Flan-T5_Name-recognition
## Description
Finetune Flan T5 model for Finnish person name recognition

Model: pretrained Flan T5-base
Data: https://github.com/mpsilfve/finer-data

## Demo
performance before fine-tuning: 
```
INPUT: ['find person names in: Electronic Frontier Finland ry perustaa muistopalkinnon kannustaakseen muita jatkamaan edesmenneen Ville Oksasen jalanjäljissä .']
OUTPUT: find person names in: Electronic Frontier Finland ry perustaa muistopalkinnon kannustaakseen muitotalinen kannustaakseen edesmenneen Ville Oksasen
```
performance after fine-tuning:
```
INPUT: ['find person names in: Electronic Frontier Finland ry perustaa muistopalkinnon kannustaakseen muita jatkamaan edesmenneen Ville Oksasen jalanjäljissä .']
OUTPUT: Ville Oksasen
```
