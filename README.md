public class BusquedaLinealRecursiva {
    public static int buscar(int[] arr, int x, int i) {
        if (i >= arr.length) return -1;
        if (arr[i] == x) return i;
        return buscar(arr, x, i + 1);
    }

}
