# Boring Fade-in

- Boring Fade-in

{
  0% { opacity: 0; }
  100% { opacity: 1; }
}


- Not So Boring Fade-in

{
  0% { opacity: 0; filter: brightness(1) blur(20px) }
  10% { opacity: 1; filter: brightness(1.25) blur(10px) }
  100% { opacity: 1; filter: brightness(1) blur(0) }
}