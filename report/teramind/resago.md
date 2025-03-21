%desarrollo
    \section{Resultados de la prueba de concepto}
    Whip Solutions ha llevado la prueba de concepto de DNS Filter en conjunto con Nemotek del día 28 de junio del 2024 al día 19 de julio del 2024, tras este proceso de PoC podemos visualizar la siguiente información en la plataforma de DNS Filter.

    \begin{figure}[H] 
        \centering 
        \includegraphics[width=0.9 \linewidth]{\first} 
        \caption{Vista General} 
    \end{figure} 

    Se puede observar el total de peticiones, peticiones permitidas, peticiones bloqueadas y las amenazas que se tuvieron durante dicho proceso, la prueba se llevó a cabo con 3 clientes que se instalaron sobre sus dispositivos, se desplegaron diversas políticas con las cuales se probaron las funciones de DNS Filter.
    Se configuró solo un sitio y de este se pueden obtener las siguientes métricas. 

    \begin{figure}[H] 
        \centering 
        \includegraphics[width=0.9 \linewidth]{\second} 
        \caption{Métricas Totales} 
    \end{figure} 

    Podemos visualizar el top 5 de DNS más consultados en todo nuestro tráfico, además de las categorías a las que pertenecen. Se identificaron las amenazas que fueron bloqueadas y las que fueron permitidas. También se puede observar cuáles clientes realizaron más peticiones permitidas, cuáles peticiones fueron de amenazas y cuáles fueron bloqueadas. Además, se registraron los usuarios que realizaron todas estas consultas. Esto nos permite monitorizar el uso de los dispositivos y la red que estamos supervisando, brindando una vista completa de todas las consultas realizadas.

    \begin{figure}[H] 
        \centering 
        \includegraphics[width=0.9 \linewidth]{\daa} 
        \caption{Top de DNS de las peticiones totales y categorías} 
    \end{figure}

    \begin{figure}[H]
        \centering
        \includegraphics[width=0.9 \linewidth]{\dta}
        \caption{Top de DNS de las peticiones maliciosas permitidas}
    \end{figure}

    \begin{figure}[H]
        \centering
        \includegraphics[width=0.9 \linewidth]{\dtb}
        \caption{Top de DNS de las peticiones maliciosas denegadas}
    \end{figure}

    \begin{figure}[H]
        \centering
        \includegraphics[width=0.9 \linewidth]{\cra}
        \caption{Top de Roaming client con peticiones permitidas}
    \end{figure}

    \begin{figure}[H]
        \centering
        \includegraphics[width=0.9 \linewidth]{\crb}
        \caption{Top de Roaming client con peticiones denegadas}
    \end{figure}

    \begin{figure}[H]
        \centering
        \includegraphics[width=0.9 \linewidth]{\cta}
        \caption{Top de Roaming client con peticiones maliciosas permitidas}
    \end{figure}

    \begin{figure}[H]
        \centering
        \includegraphics[width=0.9 \linewidth]{\ctb}
        \caption{Top de Roaming client con peticiones maliciosas denegadas}
    \end{figure}

    \begin{figure}[H]
        \centering
        \includegraphics[width=0.9 \linewidth]{\tbc}
        \caption{Amenazas por categoría}
    \end{figure}

    \begin{figure}[H]
        \centering
        \includegraphics[width=0.9 \linewidth]{\tbr}
        \caption{Amenazas por cliente}
    \end{figure}   

    \begin{figure}[H]
        \centering
        \includegraphics[width=0.9 \linewidth]{\tbd}
        \caption{Amenazas por dominio}
    \end{figure}    
    
    \begin{figure}[H]
        \centering
        \includegraphics[width=0.9 \linewidth]{\tbs}
        \caption{Amenazas por sitio}
    \end{figure}

    \begin{figure}[H]
        \centering
        \includegraphics[width=0.9 \linewidth]{\tbu}
        \caption{Amenazas por usuario}
    \end{figure}
    
    \begin{figure}[H]
        \centering
        \includegraphics[width=0.9 \linewidth]{\ra}
        \caption{Peticiones totales permitidas}
    \end{figure}
    
    \begin{figure}[H]
        \centering
        \includegraphics[width=0.9 \linewidth]{\rb}
        \caption{Peticiones totales denegadas}
    \end{figure}

    \begin{figure}[H]
        \centering
        \includegraphics[width=0.9 \linewidth]{\ta}
        \caption{Amenazas totales permitidas}
    \end{figure}

    \begin{figure}[H]
        \centering
        \includegraphics[width=0.9 \linewidth]{\tb}
        \caption{Amenazas totales denegadas}
    \end{figure}
    
    \begin{figure}[H]
        \centering
        \includegraphics[width=0.9 \linewidth]{\total}
        \caption{Trafico Total en la red}
    \end{figure} 