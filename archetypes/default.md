+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
lastmod: {{ now.Format "2006-01-02" }}
+++
{{ if .Lastmod }}
    <p>Última modificación: {{ .Lastmod.Format "2006-01-02" }}</p>
{{ end }}
