Để giải bài tập trong hình, chúng ta sẽ đi qua từng bước. Bài toán yêu cầu chứng minh rằng giá trị kỳ vọng của động lượng \(\langle \hat{p}_x \rangle = 0\) nếu \(\phi(x)\) là hàm thực đối với hạt ở trạng thái \(\psi(x) = \phi(x) e^{ip_0x/\hbar}\).

1. **Hàm sóng và toán tử động lượng**:
   - Hàm sóng được cho là \(\psi(x) = \phi(x) e^{ip_0x/\hbar}\).
   - Toán tử động lượng trong cơ học lượng tử là \(\hat{p}_x = -i\hbar \frac{d}{dx}\).

2. **Giá trị kỳ vọng của động lượng**:
   Giá trị kỳ vọng của động lượng \(\hat{p}_x\) được định nghĩa là:
   \[
   \langle \hat{p}_x \rangle = \int_{-\infty}^{\infty} \psi^*(x) \left( -i\hbar \frac{d}{dx} \right) \psi(x) \, dx
   \]
   Trong đó \(\psi^*(x)\) là liên hợp phức của \(\psi(x)\).

3. **Tính toán \(\psi^*(x)\)**:
   \[
   \psi^*(x) = \phi^*(x) e^{-ip_0x/\hbar}
   \]
   Nếu \(\phi(x)\) là hàm thực thì \(\phi^*(x) = \phi(x)\).

4. **Thay \(\psi(x)\) và \(\psi^*(x)\) vào biểu thức giá trị kỳ vọng**:
   \[
   \langle \hat{p}_x \rangle = \int_{-\infty}^{\infty} \phi(x) e^{-ip_0x/\hbar} \left( -i\hbar \frac{d}{dx} \right) \left[ \phi(x) e^{ip_0x/\hbar} \right] \, dx
   \]

5. **Tính toán đạo hàm bên trong tích phân**:
   \[
   \frac{d}{dx} \left[ \phi(x) e^{ip_0x/\hbar} \right] = \phi'(x) e^{ip_0x/\hbar} + \phi(x) \frac{ip_0}{\hbar} e^{ip_0x/\hbar}
   \]
   Do đó:
   \[
   \left( -i\hbar \frac{d}{dx} \right) \left[ \phi(x) e^{ip_0x/\hbar} \right] = -i\hbar \left( \phi'(x) e^{ip_0x/\hbar} + \phi(x) \frac{ip_0}{\hbar} e^{ip_0x/\hbar} \right)
   \]

6. **Thay đạo hàm vào tích phân**:
   \[
   \langle \hat{p}_x \rangle = \int_{-\infty}^{\infty} \phi(x) e^{-ip_0x/\hbar} \left[ -i\hbar \phi'(x) e^{ip_0x/\hbar} - i p_0 \phi(x) e^{ip_0x/\hbar} \right] \, dx
   \]

7. **Phân tách tích phân**:
   \[
   \langle \hat{p}_x \rangle = \int_{-\infty}^{\infty} \phi(x) \left[ -i\hbar \phi'(x) \right] \, dx