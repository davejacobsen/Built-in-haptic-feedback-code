## Built-in-haptic-feedback-code

### Quickly see and implement the 9 built in types of haptic feedback to add it to your project!

##### -Create a struct with static functions containing any of the 9 built in haptics you wish to use
##### -Then call a function anywhere in your project without retyping the code within the function each time
```
import UIKit

struct Haptics {   
    
    // Light Impact
    static func playLightImpact() {
        let generator = UIImpactFeedbackGenerator(style: .light)
        generator.impactOccurred()
    }
    
    // Medium Impact
    static func playMediumImpact() {
        let generator = UIImpactFeedbackGenerator(style: .medium)
        generator.impactOccurred()
    }
    
    // Heavy Impact
    static func playHeavyImpact() {
        let generator = UIImpactFeedbackGenerator(style: .heavy)
        generator.impactOccurred()
    }
    
    // Rigid Impact
    static func playRigidImpact() {
        let generator = UIImpactFeedbackGenerator(style: .light)
        generator.impactOccurred()
    }
    
    // Soft Impact
    static func playSoftImpact() {
        let generator = UIImpactFeedbackGenerator(style: .light)
        generator.impactOccurred()
    }
    
    // Success Notification
    static func playSuccessNotification() {
        let generator = UINotificationFeedbackGenerator()
        generator.notificationOccurred(.success)
    }
    
    // Error Notification
    static func playErrorNotification() {
        let generator = UINotificationFeedbackGenerator()
        generator.notificationOccurred(.error)
    }
    
    // Warning Notification
    static func playWarningNotification() {
        let generator = UINotificationFeedbackGenerator()
        generator.notificationOccurred(.warning)
    }
    
    // Selection Changed
    static func playSelectionChanged() {
        let generator = UISelectionFeedbackGenerator()
        generator.selectionChanged()
    }
}
```
