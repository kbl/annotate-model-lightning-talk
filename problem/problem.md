!SLIDE commandline incremental

# Rails model

    $ script/generate model user name:string age:integer address_id:integer email:string active:boolean
    $ rake db:migrate
    
    $ less User.rb

    class User < ActiveRecord::Base
    end


!SLIDE commandline incremental

    $ script/generate migration add_xxx_to_user
    $ rake db:migrate
    $ script/generate migration remove_xxx_from_user
    $ rake db:migrate


!SLIDE

# hundred migrations later #

    @@@ ruby
    class User < ActiveRecord::Base
    end


!SLIDE full-page-image center

# Problem? #

![Problem?](problem.jpg)
