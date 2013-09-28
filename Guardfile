guard :coffeescript do
  watch(%r(.*\.coffee)){|m| `coffee -c #{m[0]}`}
end

guard :coffeescript do
  watch(%r(.*\.haml)){|m| `bundle exec haml  #{m[0]} > #{m[0].gsub("haml","html")}`}
end
