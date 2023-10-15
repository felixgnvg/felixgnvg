import pygame
import sys

# Initialize Pygame
pygame.init()

# Set up game window
screen = pygame.display.set_mode((800, 600))
pygame.display.set_caption("Adventure Game")

# Game loop
running = True
while running:
    for event in pygame.event.get():
        if event.type == pygame.QUIT:
            running = False

    # Update game logic here

    # Draw game elements here

    pygame.display.update()

# Quit Pygame
pygame.quit()
sys.exit()
 
