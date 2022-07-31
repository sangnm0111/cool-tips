# Boring Fade-in

- Boring Fade-in

```
{
  0% { opacity: 0; }
  100% { opacity: 1; }
}
```
![boring-fade-in](https://user-images.githubusercontent.com/55726998/182012266-66870727-2af4-477c-b4c8-a6ea9989c570.gif)

- Not So Boring Fade-in

```
{
  0% { opacity: 0; filter: brightness(1) blur(20px) }
  10% { opacity: 1; filter: brightness(1.25) blur(10px) }
  100% { opacity: 1; filter: brightness(1) blur(0) }
}
```
![not-boring-fade-in](https://user-images.githubusercontent.com/55726998/182012269-1c98af06-aee4-4b70-9453-c66e5d8faf43.gif)
