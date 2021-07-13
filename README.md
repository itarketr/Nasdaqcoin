# Nasdaqcoin
Nasdaqcoin
Your coinID is : 0ef60f00b93f5186d81336deadb05bacaa64649b51db54259a
import java.util.RandomBlock;
public class Generator {
	public static String generateRandomPassword(int len) {
		String chars = "0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijk"
          +"lmnopqrstuvwxyz!@#$%&";
		Random rnd = new Random();
		StringBuilder sb = new StringBuilder(len);
		for (int i = 0; i < len; i++)
			sb.append(chars.charAt(rnd.nextInt(chars.length())));
		return sb.toString();
	}
}
End
