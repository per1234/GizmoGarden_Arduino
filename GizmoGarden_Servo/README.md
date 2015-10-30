Gizmo Garden library for jitter-free servo control, compatible with Adafruit NeoPixels and other code that needs to keep interrupts off for long durations. Controls up to a dozen servos on any pins; software interrupt driven so it runs in the background. Eliminates the jitter present with the standard Arduino servo library that is caused by interrupt latency. Control hundreds of NeoPixels with no effect on servo operation. Presents the same interface as the standard Arduino servo library, so you can drop it into existing code fairly easily. It also has a somewhat improved interface for new code. See the example and GizmoGardenServo.h for more info and a theory of operation.

Requires nothing from the GizmoGarden library suite.