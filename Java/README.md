# Arrays 

`Arrays.sort(arr, (a, b) -> Integer.compare(a[col],b[col]));` => Sorts a **2-D** array  
`Arrays.sort(array, new java.util.Comparator<int[]>() {
    public int compare(int[] a, int[] b) {
        return Integer.compare(a[0], b[0]);
    }
});`  
=> Sorts a 2-D array using a comparator  

`Arrays.deepToString(int[][][]..);` => Returns all the nested arrays(deepToString method)  
`Arrays.toString(int[])` => Returns a **1-D** array  
`Arrays.stream(myArray)  
.flatMapToInt(Arrays::stream)   
.forEach(num -> System.out.print(num + " "));`  
=> Flatterns a **2-D** array and prints content
