int FindUnique(int arr[], int size){

  int temp = 0;
  for (int i=0; i<size; i++)
    temp^=arr[i];
  return temp;
}
