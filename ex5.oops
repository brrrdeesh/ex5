package converter;

public class TimeConverter {
    // Method to convert hours to minutes
    public static int hoursToMinutes(double hours) {
        return (int) (hours * 60);
    }

    // Method to convert hours to seconds
    public static int hoursToSeconds(double hours) {
        return (int) (hours * 3600);
    }

    // Method to convert minutes to hours
    public static double minutesToHours(int minutes) {
        return (double) minutes / 60;
    }

    // Method to convert seconds to hours
    public static double secondsToHours(int seconds) {
        return (double) seconds / 3600;
    }
}

package main;
import converter.TimeConverter;

public class Main {
    public static void main(String[] args) {
        double hours = 2.5; // Replace with your desired input
        int minutes = TimeConverter.hoursToMinutes(hours);
        int seconds = TimeConverter.hoursToSeconds(hours);

        System.out.println(hours + " hours is equivalent to:");
        System.out.println(minutes + " minutes");
        System.out.println(seconds + " seconds");

        int inputMinutes = 150; // Replace with your desired input
        int inputSeconds = 7200; // Replace with your desired input
        double convertedHoursFromMinutes = TimeConverter.minutesToHours(inputMinutes);
        double convertedHoursFromSeconds = TimeConverter.secondsToHours(inputSeconds);

        System.out.println(inputMinutes + " minutes is equivalent to " + convertedHoursFromMinutes + " hours.");
        System.out.println(inputSeconds + " seconds is equivalent to " + convertedHoursFromSeconds + " hours.");
    }
}
