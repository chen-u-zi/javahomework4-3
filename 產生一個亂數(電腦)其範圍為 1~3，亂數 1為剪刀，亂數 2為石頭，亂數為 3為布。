# myjavahomework
程式碼作業收集區

package ch5;

import java.util.Scanner;

public class ex2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("來一局勝負吧!");
		System.out.println("-----------------------------------");
		Scanner input = new Scanner(System.in);//讓玩家輸入的東東
		int gamer;//玩家ouob
		int computer;//電腦onop
		boolean flag = true;
		String yn = "Y";
		while (flag) {
			System.out.println("請輸入：（1.石頭、2.剪刀  、3.布 ）");
			gamer = input.nextInt();//把玩家輸入的東西讀取到玩家ouob

			computer = (int) (Math.random() * 3) + 1; // 另一種產生隨機數的方法如下被註釋的內容
			// Random r=new Random();
			// int computer = r.nextInt(3)+1;

			System.out.print("結果爲：");
			if (gamer == 1) {
				flag = false;
				// String strGamer = "石頭";
				if (computer == 1) {
					// String strComputer = "石頭";
					System.out.print("平局。" + "\n你出的石頭，電腦出的石頭");
					// System.out.print("平局"+"\n"+"你出的"+strGamer+"，電腦出的"+strComputer);
				} else if (computer == 0)
					System.out.print("你獲勝了！" + "\n你出的石頭，電腦出的剪刀");
				else
					System.out.print("電腦獲勝了。" + "\n你出的石頭，電腦出的布");
			} else if (gamer == 2) {
				flag = false;
				if (computer == 2)
					System.out.print("平局" + "\n你出的剪刀，電腦出的剪刀");
				else if (computer == 3)
					System.out.print("你獲勝了！" + "\n你出的剪刀，電腦出的布");
				else
					System.out.print("電腦獲勝了" + "\n你出的剪刀，電腦出的石頭");
			} else if (gamer == 3) {
				flag = false;
				if (computer == 3)
					System.out.print("平局" + "\n你出的布，電腦出的布");
				else if (computer == 1)
					System.out.print("你獲勝了！" + "\n你出的布，電腦出的石頭");
				else
					System.out.print("電腦獲勝了" + "\n你出的布，電腦出的剪刀");
			} else {
				System.out.println("錯誤，請重新輸入");
				flag = true;
			}
			if (flag == false) {
				System.out.println("\n是否繼續進行：（Y/N）");
				yn = input.next();
//              if (yn.charAt(0) == 'Y' || yn.charAt(0) == 'y') { //判斷區分大小寫
				if ("y".equalsIgnoreCase(yn)) {  //自動不區分大小寫
					flag = true;
				} else
					System.out.println("遊戲結束！");
			}
		}
	}

}
