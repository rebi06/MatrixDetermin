# 🧮 Matrix Determinant (Java)

A simple Java program to calculate determinants of 2x2 and 3x3 matrices.  
The user inputs the matrix elements, and the program computes the determinant.

## Features
- Supports 2x2 and 3x3 matrices
- Uses a class `MatrixDeterminant` with separate methods for 2x2 and 3x3
- Input via `Scanner`
- Clear console output of the determinant

## Example
2×2なら2を３×3なら3入力してください
2
2x2 行列の要素を入力してください:
1 2
3 4
2x2 行列式 = -2

## Technologies
- Java (Scanner, arrays, loops)
- Linear algebra basics (determinant formulas)

## Reflection (反省)
- 入力チェック（文字や不正な数字）への対応はまだ十分ではない  
- 一般の n×n 行列への拡張は未実装  
- 次は try-catch を使った例外処理や再帰的アルゴリズムを学び、拡張を目指す

## Timeline
- Project created: 2025-10-02
