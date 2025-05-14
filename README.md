 
## Abstract
The idea is to encode the sender's text`(secret message)` using the concept of interference. The secret message is encoded based on the cover file`(a text sentence in this case)`.


## Future Scopes and Improvements
The evaluation was done using three different communication protocols, namely *BB84*, *BBM92*, and *Ekert91*, I utilized a real quantum simulator named `FakeWashingtonV2()` to simulate the behavior of a real quantum computer. This simulator was chosen because it is a widely used open-source quantum simulator that can accurately simulate the behavior of a real quantum computer. By using this simulator, I was able to test the system's performance under realistic conditions and compare it with the theoretical predictions obtained through simulations.
  



**First import Fake-Provider tool, via qiskit library**. 

Import `FakeWashingtonV2`:
```bash
from qiskit.providers.fake_provider import FakeWashingtonV2
```
Alternatively, one can install the required dependencies via the requirements.txt
```bash
python3 -m pip install --user --upgrade pip && python3 -m pip install -r requirements.txt
```

