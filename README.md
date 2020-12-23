# swapna

from django.shortcuts import render
import datetime
# Create your views here.
def showdate(request):
    datetime.datetime.now()
    return render(request ,'time.html')
