{{- $l := site.Data.langs | len }}

{{- T "gltotal" $l }}

{{- if gt $l 0 }}
{{- range $k, $v := site.Data.langs }}
- {{ $k }} ({{ $v.name }}), by [{{ $v.author.name }}]({{ $v.author.link }})
{{- end }}
{{- end }}