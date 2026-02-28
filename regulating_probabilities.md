## Self Regulating Uncertainty
This elements limits how low a probability can get when updating probabilities in pre-trained datasets. Such as making sure probabilities aren't to low.

~~~ruby
puts "Level 1 Uncertainty"
2.times do
  get_neg1_statistics(:cats, "Cats are the cleanest pets.",
                      :dogs,  "Dogs are mans best friend.",
                      :gerbils, "Gerbils dont use hamster wheels.")
                      
                      dynamic_guillotine_un_allocation
end

puts "Level 2 Uncertainty"
2.times do
  get_neg2_statistics(:cats, "Cats are the cleanest pets.",
                      :dogs,  "Dogs are mans best friend.",
                      :gerbils, "Gerbils dont use hamster wheels.")
                      
                      dynamic_guillotine_un_allocation
end
~~~
