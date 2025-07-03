#  Scraper de Empresas - SuperSociedades (Colombia)

Este proyecto automatiza la recolección de información financiera de empresas registradas en el portal de la Superintendencia de Sociedades de Colombia:  
🔗 [https://siis.ia.supersociedades.gov.co/](https://siis.ia.supersociedades.gov.co/)

Utiliza **Python**, **Selenium** y **Chrome WebDriver** para navegar por el sitio web y extraer datos como:

-  Nombre de la empresa  
-  Activos  
-  Ingresos  
-  Utilidad neta  

Los resultados se guardan en un archivo Excel llamado `resultado.xlsx`.

---

##  Tecnologías Utilizadas

- Python 3.x  
- Selenium  
- WebDriver Manager  
- Pandas  
- Expresiones Regulares (re)  
- Chrome en modo headless  

---

##  Instalación de dependencias

Asegúrate de tener Python instalado y luego ejecuta:

```bash
pip install selenium pandas webdriver-manager openpyxl

```

> ℹ️ Los datos extraídos provienen del portal público de la Superintendencia de Sociedades de Colombia  
> (https://siis.ia.supersociedades.gov.co/) y son utilizados únicamente con fines educativos y demostrativos.

