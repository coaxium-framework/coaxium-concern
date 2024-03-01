# coaxium-concern
Loads `ActiveSupport::Concern`s from `app/concerns` and and includes them in the appropriate class using `ActiveSupport.on_load(&lt;underscored_class_name>)`.
