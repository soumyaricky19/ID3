# ID3
Implement ID3 algorithm on a dataset with boolean values

Executing the python code:-
python ID3.py <training_set.csv absolute path> <validation_set.csv absolute path> <test_set.csv absolute path> <pruning factor>


Instructions/assumptions:-
1. If 'prunned tree' needs to be displayed, uncomment line 300
2. If more accuracy improvement on validation set is intended, increase value of accuracy_improvement_threshold in line 8. The default value is '0'
3. If there is a tie, random from [0,1] is chosen
4. Libraries used:-
  
  print_function  -Enhanced printing formatting
  sys             -system arguments
  csv             -Reading csv file
  log             -log calculation
  random          -Random number calculation
