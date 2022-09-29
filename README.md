# sifre
import java.util.Scanner;

public class Main {
    public static void main (String []args)
    {
        Scanner input=new Scanner(System.in);

        String userName, passWord, newPassword, answer;

        System.out.print("Kullanıcı Adı: ");
        userName= input.nextLine();

        System.out.print("Şireniz: ");
        passWord= input.nextLine();

        if (passWord.equals("patika") passWord.equals("java")) {
        System.out.print("Bilgileriniz doğru ");
        }else if (userName.equals("Patika")) {

        System.out.println("Şifre sıfırlamak için (evet/hayır)=");
        answer = input.nextLine();

        if (answer.equals("evet"))
            System.out.println("Yeni Şifre Giriniz: ");
        newPassword = input.nextLine();

        if (newPassword.equals("java")) {
            System.out.println("Şifre oluşturuldu");

        } else {
            System.out.println("İşlem sonuçlandırıldı");

        }
    }

    }

}
