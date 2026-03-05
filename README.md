# Stallkarte
Stallkarte für Hähnchen
class DayEntry {

  int day;

  int deaths1;
  int deaths2;

  int selection1;
  int selection2;

  double weightTarget;
  double weightActual;

  double feedTarget;
  double feedActual;

  double waterTarget;
  double waterActual;

  DayEntry({

    required this.day,

    required this.deaths1,
    required this.deaths2,

    required this.selection1,
    required this.selection2,

    required this.weightTarget,
    required this.weightActual,

    required this.feedTarget,
    required this.feedActual,

    required this.waterTarget,
    required this.waterActual,

  });

}
