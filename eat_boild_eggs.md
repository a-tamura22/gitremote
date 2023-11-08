```mermaid
graph TD;
subgraph one
　B[ゆで卵を食べる];
end
　subgraph two
  B-->C[卵を買う];
  B-->F[ゆで卵を作る];
   B-->J[食べる準備をする];
   end
   subgraph three
  C-->D[銀行で金を下ろす];
  D-->E[スーパーで卵を買う];
  F-->G[卵を洗う];
  
  G-->H[お湯を沸かす];
  H-->I[卵をゆでる];
  J-->K[腹筋しておなかを減らす];
  K-->L[殻を割る];
  L-->M[塩を振る];
end
  
  