# [FAMFAMFAM flag icons](http://tkrotoff.github.com/famfamfam_flags/)

[FAMFAMFAM flag icons](http://famfamfam.com/lab/icons/flags/) by Mark James.

To get started, checkout http://tkrotoff.github.com/famfamfam_flags/

If you are using Ruby on Rails, check https://github.com/tkrotoff/famfamfam_flags_rails

## Sprite generation using glue

    glue . . --sprite-namespace= --namespace=famfamfam-flag --each-template="%(class_name)s { background-position: %(x)s %(y)s; width: %(width)s; height: %(height)s; }\n"
