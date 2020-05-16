# Adaptive grid layout based on flexbox

### Structure description

##### Grid Layout has the following structure:
The ‘jlab-row’ class defines a row that occupies 100% of the width of the parent component.</br>
The class ‘jlab-cell- $’, where $ is a number from 1 to 12, takes $ / 12 of the width of jlab-row.


### Features

- the cell doesn't move to the next line when adding / changing the border;
- resizing the page does not affect the location of the cells - they do not go to the next line.

### HTML code example
    <div class="container">
         <div class="jlab-row">
             <div class="jlab-cell-6">
             <h3>6/12</h3>
             </div>
             <div class="jlab-cell-6">
             <h3>6/12</h3>
         </div>
    </div>


