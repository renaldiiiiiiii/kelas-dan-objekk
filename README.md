public class sepatu {

	string warna = "hitam";
	string merk = "adidas";
	void kering() {
		System.out.println("sepatu " + " warna " + warna + " siap dipaki");
	}
	void basah() {
		System.out.println("sepatu " + " warna " + warna +"masih basah ");
	}
	public static void main(string[] args) {
		sepatu sepatusaya = new sepatu();
		sepatusaya.kering();
		sepatusaya.basah();
	}
}
