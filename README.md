Q1. Create a dict with name and mobile number.Define a GUI interface using tkinter and pack the label and
create a scrollbar to scroll the list of keys in the dictionary.

Sol:-
from tkinter import *

master = Tk()

scrollbar = Scrollbar(master)
scrollbar.pack(side=RIGHT, fill=Y)

listbox = Listbox(master, yscrollcommand=scrollbar.set)
for i in range(1):
    listbox.insert(END,"happy ",str("89273957"))
    listbox.insert(END,"arun ",str("098750299"))
    listbox.insert(END,"sid ",str("89273957"))
    listbox.insert(END,"mack ",str("098750299"))
    listbox.insert(END,"jinkul ",str("89273957"))
    listbox.insert(END,"papu ",str("098750299"))
    listbox.insert(END,"chandu ",str("89273957"))
    listbox.insert(END,"arun ",str("9374709094"))
    listbox.insert(END,"sheera ",str("2435456"))
    listbox.insert(END,"tiger zinda hai",str("9508975495"))
listbox.pack(side=LEFT, fill=BOTH)

scrollbar.config(command=listbox.yview)

mainloop()
