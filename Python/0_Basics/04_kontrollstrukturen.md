```py
alter = 101

if (alter >= 18 and alter <= 100):
	print ("Sie sind volljährig!")
elif (alter > 100):
	print ("Testament wurde erstellt!")
else:
	print ("Du bist nicht volljährig")
```
```py
# Schöner

alter = 101

if (alter > 100):
	print ("Testament wurde erstellt!")
elif (alter >= 18):
	print ("Sie sind volljährig!")
else:
	print ("Du bist nicht volljährig")
```