# RAP Travel Management App (ABAP RESTful Application Programming Model)

This project implements a simplified Travel Management application using SAP BTP ABAP Environment and the ABAP RESTful Application Programming Model (RAP).


## Features

- Travel table with fields like agency, customer, dates, prices
- CDS-based UI with Fiori Elements
- Attachment, metadata extension, and draft handling
- Create, update, and delete entries via auto-generated Fiori UI
----------------------
<img width="1388" alt="preview_list_page" src="https://github.com/user-attachments/assets/a8089ed7-41fa-4fd5-8d48-0b4124427891" />

----------------------

<img width="1387" alt="preview_object_page" src="https://github.com/user-attachments/assets/52e55e4e-616b-46ec-8a8c-ff605f889c64" />

----------------------
<img width="1390" alt="preview_object_page_2" src="https://github.com/user-attachments/assets/2013a2da-d014-4fb9-8aa4-5ba62a144560" />

----------------------

<img width="1079" alt="currency_selection_popup" src="https://github.com/user-attachments/assets/d5595cbc-19a2-4fcd-94ad-46c4150df2f4" />



---

## Technologies used

    SAP BTP ABAP Environment (Trial)

    ABAP RESTful Application Programming Model (RAP)

    Eclipse with ADT (ABAP Development Tools)

    CDS Views, Annotations

    Fiori Elements Preview

    GitHub for version control

## ⚠️ Disclaimer

This project was originally implemented and tested on a SAP BTP ABAP Trial system, which automatically expired after 90 days.
    As a result, the source files were manually reconstructed based on memory, screenshots, and the official SAP tutorial.
    Some content in the RAP_SOURCE_CODE/ folder may differ slightly from the original implementation, but the overall structure and concepts are preserved to showcase the full RAP architecture and development process.
    
## How to reproduce

    Clone this repo in Eclipse (ADT)

    Use the ABAP trial system (CB9980001691 or similar)

    Activate the travel table (ZRAP100_ATRAV2)

    Generate data using the class ZCL_RAP100_GEN_DATA_XXXX

    Open the service binding preview to see the app
## Tutorial Reference

This app was created by following this tutorial: (https://developers.sap.com/tutorials/abap-environment-rap100-generate-ui-service.html)
SAP Developer Center - Generate UI from RAP





