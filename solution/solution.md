!SLIDE full-page-image center

# Solution! #

![Easy solution](triangle.jpg)


!SLIDE

# <a href="http://pragdave.pragprog.com/pragdave/2006/02/annotate_models.html">
Annotate Plugin
</a> 
# <a href="http://github.com/ctran/annotate_models">AnnotateModel Gem</a> #


!SLIDE commandline incremental

    $ cd rails_project
    $ annotate
    $ > Annotated (1): User


!SLIDE

    @@@ ruby
    class User < AbstractRecord::Base
    end

    # == Schema Information
    #
    # Table name: users
    #
    #  id         :integer         not null, primary key
    #  name       :string(255)
    #  age        :integer
    #  address_id :integer
    #  email      :string(255)
    #  active     :boolean
    #  created_at :datetime
    #  updated_at :datetime
    #


!SLIDE bullets incremental

# Comments in #

* ActiveRecord models
* Fixture files
* Tests and Specs
* Object Daddy exemplars
* Machinist blueprints


!SLIDE

# For more read gem <a href="http://github.com/ctran/annotate_models/blob/master/README.rdoc">rdoc</a> #

