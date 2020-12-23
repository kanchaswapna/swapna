# swapna

from django.shortcuts import render
from django.http import HttpResponse
# Create your views here.
def learn_var(rquest):
    a = '<h1> heelo</h1>'
    return HttpResponse(a)

def learn_math(request):
    a = 15 + 5
    return HttpResponse(a)

def learn_format(request):
    a = 'swapna'
    return HttpResponse(f'hello world {a}')
