guard 'livereload' do
  watch(%r{views/.+\.(erb|haml|slim)$})
  watch(%r{stylesheets/.+\.(sass|scss)})
  watch(%r{public/.+\.(css|js|html)})
  watch(%r{config/locales/.+\.yml})
  # Rails Assets Pipeline
  watch(%r{(app|vendor)(/assets/\w+/(.+\.(css|js|html|png|jpg))).*}) { |m| "/assets/#{m[3]}" }
end
