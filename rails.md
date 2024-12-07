# To prepare a database first time
fly ssh console -C "bin/rails db:prepare"


# To update a database with seeds.rb
fly ssh console -C "bin/rails db:seed"
