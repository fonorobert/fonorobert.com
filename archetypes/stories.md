+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
draft = true
featured_image = ""
+++

{{< gallery "gallery-1" "grid"
"IMAGE-PATH.jpg :: CAPTION"
>}}