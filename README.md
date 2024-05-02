[['-', '-', '-', '-', '-', '-', '-', '-'],
         ['-', '-', '-', '-', '-', '-', '-', '-'],
         ['-', '-', '-', '-', '-', '-', '-', '-'],
         ['-', '-', '-', '-', '-', '-', '-', '-'],
         ['-', '-', '-', '-', '-', '-', '-', '-'],
         ['-', '-', '-', '-', '-', '-', '-', '-'],
         ['-', '-', '-', '-', '-', '-', '-', '-'],
         ['-', '-', '-', '-', '-', '-', '-', '-']]
    'white_pawn': pygame.image.load('images/white_pawn.png'),
    'black_pawn': pygame.image.load('images/black_pawn.png'),
    'white_rook': pygame.image.load('images/white_rook.png'),
    'black_rook': pygame.image.load('images/black_rook.png'),
    'white_knight': pygame.image.load('images/white_knight.png'),
    'black_knight': pygame.image.load('images/black_knight.png'),
    'white_bishop': pygame.image.load('images/white_bishop.png'),
    'black_bishop': pygame.image.load('images/black_bishop.png'),
    'white_queen': pygame.image.load('images/white_queen.png'),
    'black_queen': pygame.image.load('images/black_queen.png'),
    'white_king': pygame.image.load('images/white_king.png'),
    'black_king': pygame.image.load('images/black_king.png')
}
for row in range(8):
    for col in range(8):
        if board[row][col] == 'white_pawn':
            screen.blit(pieces['white_pawn'], (col * 50, row * 50))
        elif board[row][col] == 'black_pawn':
            screen.blit(pieces['black_pawn'], (col * 50, row * 50))
        elif board[row][col] == 'white_rook':
