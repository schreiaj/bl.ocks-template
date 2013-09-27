guard :coffeescript do
  watch(%r(.*\.coffee)){|m| `coffee -c #{m[0]}`}
end

guard :coffeescript do
  watch(%r(.*\.md)){|m| `md2html -c #{m[0]} > #{m[0].gsub("md","html")}`}
end
