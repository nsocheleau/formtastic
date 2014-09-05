appraise 'rails-3.0' do
  gem 'rails',      '~> 3.0.0'
end

appraise 'rails-3.1' do
  gem 'rails',      '~> 3.1.0'
end

appraise 'rails-3.2' do
  gem 'rails', '~> 3.2.0'
end

appraise 'rails-4' do
  gem 'rails', '~> 4.0.0'
end

# Special case for a change in I18n
appraise 'rails-4.0.4' do
  gem 'rails', '4.0.4'
end

appraise 'rails-4.1' do
  gem 'rails', '~>4.1.0'
end

appraise 'rails-4.2' do
  gem 'rails', '~>4.2.0.beta1'
end

if ENV["RAILS_EDGE"] == "true"
  appraise 'rails-edge' do
    gem 'rails', :git => 'git://github.com/rails/rails.git'
  end
end
