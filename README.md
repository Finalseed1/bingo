#Game Engine

1. 초기화 합니다.
	1.1 빙고판 초기화 합니다.

	2. 유저 입력 받는다.
		
	3. 처리한다.
		3.1 사용자 처리를 한다.
			3.1.1 빙고 처리를 해본다.
				3.1.1.1 빙고판에서 유저가 입력한 숫자를 찾는다.
				3.1.1.2 빙고가 있는지 확인한다.
		
                 12x
             xx6
             78x

             i)
             가로 경우
             0 == 'x' and 1 == 'x' and 2 == 'x'
             3 == 'x' and 4 == 'x' and 5 == 'x'            
             6 == 'x' and 7 == 'x' and 8 == 'x'

             세로 경우
             0 == 'x' and 3 == 'x' and 6 == 'x'
             3 == 'x' and 4 == 'x' and 5 == 'x'            
             6 == 'x' and 7 == 'x' and 8 == 'x'

            대각선 경우
             0 == 'x' and 4 == 'x' and 8 == 'x'
             2 == 'x' and 4 == 'x' and 6 == 'x'


	
	//if (BingoPlayerMap[0] == 'X' && BingoPlayerMap[1] == 'X' && BingoPlayerMap[2] == 'X')
	//{
         // cout << 'Bingo' << endl;
	//}
	// elso if (BingoPlayerMap[3] == 'X' && BingoPlayerMap[4] == 'X' && BingoPlayerMap[5] == 'X') 하던지 아니면 for로 반복 없앰

	for (int i = 0; i <= 6; i = i + 3)
	{
		if (BingoPlayerMap[i + 0] == 'X' &&
			BingoPlayerMap[i + 3] == 'X' &&
			BingoPlayerMap[i + 6] == 'X'&&)
		{
			cout << "Bingo" << endl;
		}
	}

		
	4. 그린다.
		4.1 사용자 그리기를 한다.
			4.1.1 빙고판을 그린다.

5. 종료 합니다.