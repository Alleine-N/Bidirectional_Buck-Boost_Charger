# Bidirectional_Buck-Boost_Charger
Battery charging system based on a buck-boost topology. It implements a cascade controller to ensure dual battery charging mode: Constant current and constant voltage. This ensures mantaining optimal state of charge and optimal state of health.

## Controller logic 
The cascade control consists of two PI controllers and switching logic that ensures the possiblity of changing between constant current and constant voltage, depending on the needs of the battery. It also allows to discharge the battery as neeeded and ensures that the voltage of the battery does not go below the minimum voltage to mantain the health of the battery.
