{% comment %}This reusable is only to be used in other repo/org/enterprise setting reusables.{%- endcomment -%}
1. In the left sidebar, click {% ifversion fpt or ghec or ghes > 3.4 or ghae-issue-5658 %}{% octicon "play" aria-label="The {% data variables.product.prodname_actions %} icon" %} **Actions**, then click **Runner groups**.{% else %}**Actions**.{% ifversion ghes > 3.3 or ghae-issue-5091 %}
1. En la barra lateral izquierda, debajo de "Acciones"; haz clic en **Grupos ejecutores**.
{%- elsif ghes > 3.1 or ghae %}
1. En la barra lateral izquierda, debajo de "Acciones", haz clic en **Ejecutores**.{% endif %}{% endif %}