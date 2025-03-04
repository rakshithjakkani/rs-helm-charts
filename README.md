# helm  commands 
helm install --debug --dry-run <ReleaseName>./mychart --> to get the rendered chart
helm get manifest <ReleaseName> --> to the entire manifest of a release


 food: {{ .Values.favorite.food | upper | quote }}  

 drink: {{ .Values.favorite.drink | default "tea" | quote }}