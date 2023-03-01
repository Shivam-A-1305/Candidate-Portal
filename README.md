# Candidate-Portal
consist of a text dcument with superuser details
The App name is Portal in Project Candidate

Models.py
consists of 4 fieds

views.py
creating a function CastVote which is supposed to increment vote count
there is a GET API (function info)and POST API(function Vote)

ur;s.py
urlpatterns = [
    path('info/', views.info),
    path('vote/', views.Vote),

]
