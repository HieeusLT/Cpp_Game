# Game-Project

# Game Tic Tac Toe đơn giản 3x3 gồm 2 chế độ chơi
- Chơi với người : 2 người chơi sẽ tự chơi với nhau. 
- Chơi với AI : người chơi sẽ chơi với AI (sử dụng thuật toán minimax : https://vi.wikipedia.org/wiki/Minimax ).

# Áp dụng thuật toán minimax để tính điểm hiệu quả của từng nước đi:
- Dùng hàm đệ quy tới khi thỏa mãn điều kiện game kết thúc để xác định độ hiệu quả của nước đi, nếu nước đi đó dẫn đến chiến thắng thì sẽ trả về giá trị là 1 còn nếu nước đi dẫn đến thua thì sẽ trả về giá trị là -1.
- Khi AI xét một nước đi bất kỳ hàm đệ quy sẽ thực hiện điền X hoặc O tùy vào lượt đi nếu vị trí đó là trống, hàm sẽ lặp đi lặp lại việc chọn vị trí như vậy cho tới khi thỏa mãn điều kiện game kết thúc hoặc khi đã điền hết 9 ô và trả về một giá trị. Sau khi tính ra được giá trị hiệu quả của nước đi đó ta sẽ trả nó về dạng ô trống ban đầu.
# Thông qua thuật toán minimax tìm nước đi tốt nhất cho AI :
- Cho AI thực hiện lần lượt các nước đi còn thỏa mãn trên bảng và tính ra số điểm hiệu quả của từng nước đi đó nhờ vào minimax, so sánh các giá trị điểm với nhau để tìm ra nước đi hiệu quả nhất.
