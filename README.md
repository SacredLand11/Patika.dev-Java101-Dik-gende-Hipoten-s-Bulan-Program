# Patika.dev-Java101-Dik-gende-Hipoten-s-Bulan-Program
Üç kenar uzunluğunu kullanıcıdan aldığınız üçgenin alanını hesaplayan programı yazınız.
## Code
public class Giris
{
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        double[] triangle = new double[3];
        for(int i = 0; i<triangle.length; i++){
            triangle[i] = s.nextDouble();
        }
        double u = (triangle[0]+triangle[1]+triangle[2])/2;
        double a = u-triangle[0];
        double b = u-triangle[1];
        double c = u-triangle[2];
        double area = Math.sqrt(u*a*b*c);
        System.out.print(area);
    }
}
