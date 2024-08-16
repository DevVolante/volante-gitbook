# Diseño Arquitectónico Volante



{% @mermaid/diagram content=&quot;gráfico TD
    subgrafo Emisores de activos
        A[Emisores de activos]
    fin

    Desarrolladores de subgrafos
        B[Desarrolladores]
    fin

    subgrafo Usuarios finales
        C[Usuarios finales]
    fin

    subgrafo Carteras
        D[Carteras]
    fin

    subgrafo DApps
        E[DApps]
    fin

    subgrafo DeFi
        F [Minería de liquidez]
        G[Préstamo]
    fin

    subgrafo Comercio electrónico
        H[Comerciantes]
    fin

    subgrafo Puentes
        Yo[Otras cadenas de bloques]
    fin

    A --&gt;|Emitir activos| mi
    B --&gt;|Desarrollar| mi
    C --&gt;|Usar| mi
    C --&gt;|Usar| F
    C --&gt;|Usar| GRAMO
    C --&gt;|Usar| h
    D --&gt;|Tienda| C
    E --&gt;|Acceso| C
    F --&gt;|Proporcionar liquidez| C
    G --&gt;|Prestar| C
    H --&gt;|Vender Productos| C
    Yo --&gt;|Puente| A
    Yo --&gt;|Puente| mi
    Yo --&gt;|Puente| F
    Yo --&gt;|Puente| GRAMO
    Yo --&gt;|Puente| h

    subgrafo Hiperescala
        A
        B
        C
        D
        Y
        F
        GRAMO
        h
        I
    fin&quot; %}

{% content-ref url=&quot;https://app.gitbook.com/s/75neFLuTt4qrehZw3Uip/volante-architectural-design/asset-issuers&quot; %}
[Emisores de activos] (https://app.gitbook.com/s/75neFLuTt4qrehZw3Uip/volante-architectural-design/asset-issuers)
{% contenido final-ref %}

{% content-ref url=&quot;https://app.gitbook.com/s/75neFLuTt4qrehZw3Uip/volante-architectural-design/developers&quot; %}
[Desarrolladores] (https://app.gitbook.com/s/75neFLuTt4qrehZw3Uip/volante-architectural-design/developers)
{% contenido final-ref %}

{% content-ref url=&quot;https://app.gitbook.com/s/75neFLuTt4qrehZw3Uip/volante-architectural-design/end-users&quot; %}
[Usuarios finales](https://app.gitbook.com/s/75neFLuTt4qrehZw3Uip/volante-architectural-design/end-users)
{% contenido final-ref %}

{% content-ref url=&quot;https://app.gitbook.com/s/75neFLuTt4qrehZw3Uip/volante-architectural-design/wallets&quot; %}
[Carteras] (https://app.gitbook.com/s/75neFLuTt4qrehZw3Uip/volante-architectural-design/wallets)
{% contenido final-ref %}

{% content-ref url=&quot;https://app.gitbook.com/s/75neFLuTt4qrehZw3Uip/volante-architectural-design/decentralized-applications-dapps&quot; %}
[Aplicaciones descentralizadas (dApps)](https://app.gitbook.com/s/75neFLuTt4qrehZw3Uip/volante-architectural-design/decentralized-applications-dapps)
{% contenido final-ref %}

{% content-ref url=&quot;https://app.gitbook.com/s/75neFLuTt4qrehZw3Uip/volante-architectural-design/defi-decentralized-finance&quot; %}
[DeFi (Finanzas Descentralizadas)](https://app.gitbook.com/s/75neFLuTt4qrehZw3Uip/volante-architectural-design/defi-decentralized-finance)
{% contenido final-ref %}

{% content-ref url=&quot;https://app.gitbook.com/s/75neFLuTt4qrehZw3Uip/volante-architectural-design/e-commerce&quot; %}
[Comercio electrónico](https://app.gitbook.com/s/75neFLuTt4qrehZw3Uip/volante-architectural-design/e-commerce)
{% contenido final-ref %}

{% content-ref url=&quot;https://app.gitbook.com/s/75neFLuTt4qrehZw3Uip/volante-architectural-design/bridges&quot; %}
[Puentes](https://app.gitbook.com/s/75neFLuTt4qrehZw3Uip/volante-architectural-design/bridges)
{% contenido final-ref %}

