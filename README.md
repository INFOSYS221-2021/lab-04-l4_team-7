# Lab-04

Update this README to include your team name and team members. Don't forget to record all your answers to lab 04 here.
Team 7:
Praitk Jivanji - pjiv657
Liona Sadler - lsad313

----------------------------------------------------------------------------------------------------------------------
1. int, bool, str

2.(random)
letter,
move,
computerLetter,
playerLetter,

3. lines 9 - 19 [Print statements]
 print('   |   |')
 print(' ' + board[7] + ' | ' + board[8] + ' | ' + board[9])
 print('   |   |')
 print('-----------')
 print('   |   |')
 print(' ' + board[4] + ' | ' + board[5] + ' | ' + board[6])
 print('   |   |')
 print('-----------')
 print('   |   |')
 print(' ' + board[1] + ' | ' + board[2] + ' | ' + board[3])
 print('   |   |')

4. lines 30 - 33 [If-Else condition]
 if letter == 'X':
  return ['X', 'O']
 else:
  return ['O', 'X']
  
5. For / While (26-28 [While Loop])
 while not (letter == 'X' or letter == 'O'):
  print('Do you want to be X or O?')
  letter = input().upper()

6. theBoard on line 144/145 or board on line 10;
  theBoard = [' '] * 10;
  or board[9]
  

7. def drawBoard(board):
drawBoard(board)
function takes the board and 'draws' it; placing letters in their cells by printing the 'board'

8. Checks the board, in all possible ways if the letter each cell is the same in any coloumn/diagonal/row

9. It will stop the game from running => makes the while condition invalid/ False


10. while True:
it initiates the board, player and computer letters
gets who is going first
and starts the game by setting gameIsPlaying to TRUE


