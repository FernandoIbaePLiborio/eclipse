# Utilidade Pública | Desenvolvimento


- [Utilidade Pública | Desenvolvimento](#utilidade-p%c3%bablica--desenvolvimento)
    - [JSF Capabilities](#jsf-capabilities)
    - [Open resource 'Ctrl+Shift+R' (configuração dos filtros de busca '.class, src e target')](#open-resource-ctrlshiftr-configura%c3%a7%c3%a3o-dos-filtros-de-busca-class-src-e-target)
        - [Passo a passo:](#passo-a-passo)
    - [Fast Swap](#fast-swap)

---

### JSF Capabilities
![free_marker](/static/public_utility/free_marker_IDE.png "Jsf Capabilities")

O pacote completo do JBoss Tools, atualmente causa uma certa lentidão na IDE. Fazendo com que desenvolvedores não utilizem de seus benefícios, tal como o framework HTML, sendo a necessidade utilizar o jsf Capabilities 'Ctrl+Click' | 'Ctrl+Barra' em xml/html para suporte aos objetos.
Podemos instalar conforme imagem acima, FreeMarker IDE from JBoss Tools 1.5.

----

### Open resource 'Ctrl+Shift+R' (configuração dos filtros de busca '.class, src e target')

Resultado ex:

![free_marker](/static/public_utility/open_resource_resultado.png "Resultado - Open Resources")

### Passo a passo:

![free_marker](/static/public_utility/open_resource_2.png "Filter - Open Resources")

![free_marker](/static/public_utility/open_resource_3.png "Filter .class - Open Resources")

![free_marker](/static/public_utility/open_resource_4.png "Filter src - Open Resources")

![free_marker](/static/public_utility/open_resource_5.png "Filter target - Open Resources")

### Fast Swap

[Archive](/static/public_utility/weblogic-application.xml "Enabling FastSwap In Your Application")

~~~~
<?xml version="1.0" encoding="UTF-8"?>
<weblogic-application xmlns="http://xmlns.oracle.com/weblogic/weblogic-application"
                      xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
                      xsi:schemaLocation="http://xmlns.oracle.com/weblogic/weblogic-application http://xmlns.oracle.com/weblogic/weblogic-application/1.3/weblogic-application.xsd">
    <application-param>
        <param-name>webapp.encoding.default</param-name>
        <param-value>UTF-8</param-value>
    </application-param>
    <fast-swap>
        <enabled>true</enabled>
    </fast-swap>

</weblogic-application>
~~~~

[About](https://docs.oracle.com/middleware/1213/wls/DEPGD/deployunits.htm#DEPGD156)
