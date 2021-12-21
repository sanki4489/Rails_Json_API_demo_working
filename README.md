gem for json
1.active_model_serializers

To format into Json API style , follow the steps here
1.create a new initializer file in config/initializers, eg.config/initializers/active_model_serializer.rb
2.ActiveModelSerializers.config.adapter = :json_api <-- Add the following line into file
3.This will return our data in the JSON API recommended spec.

To add nice routing for different versions, follow the steps here

1. create a api->v1 folder and add the specific controller and match up with the routes.
