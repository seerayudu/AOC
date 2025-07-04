# AOC

Count visible trees

30373

25512

65332

33549

35390

Grid
visiiblecount = 0

for each row in grid:
  for each coloum in grid(row)
     if tree is on the edge:
	   visiblecount +=1
else if tree is visible in any of the 4 directions 
       visiblecount +=1


isVisible(grid , row, col)
height = grid[row][col]

/ Looking up

for r = row-1 to 0:
if grid[r][col] >= height
  break
if all trees above shorter
return

/ Looking down

for r = row-1 to 0:
if grid[r][col] >= height
  break
if all trees above shorter
return

/ Looking left

for r = row-1 to 0:
if grid[r][col] >= height
  break
if all trees above shorter
return

/ Looking right

for r = row-1 to 0:
if grid[r][col] >= height
  break
if all trees above shorter
return


