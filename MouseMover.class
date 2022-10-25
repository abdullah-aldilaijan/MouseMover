import java.awt.Robot;
import java.util.Random;
import java.text.DateFormat;
import java.util.Date;


public class MouseMover {
    public static final int FIVE_SECONDS = 60000;
    public static final int MAX_Y = 400;
    public static final int MAX_X = 400;

    public static void main(String... args) throws Exception {
        Robot robot = new Robot();
        Random random = new Random();
        
        int i = 0;
        while (true) {
            robot.mouseMove(random.nextInt(MAX_X), random.nextInt(MAX_Y));
            Thread.sleep(FIVE_SECONDS);
            Date date = new Date();
            System.out.println(i+" at "+ DateFormat.getDateTimeInstance(DateFormat.LONG, DateFormat.LONG).format(date));
            i++;
        }
    }
}
