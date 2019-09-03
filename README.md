# KAITBM-03

<pre>
Hadoop 설치
- Cloud 가입
  > iwinv.kr
- Centos 설치
  > 신용카드 정보 제공
- download on Centos Server
  > hadoop binary file 
  > spark
    - In-Memory 기반 Data Process/ Machine Learning
    - Hadoop보다 100배 이상 빠름
  > zeppeline
    - Scala Repl(read-eval-print-loop) tool
    - Scala외에도 Option 설정으로 SQL, python, R 등 다양한 지원
- Client(Windows) tool
  > Dumy terminal 
    - Putty, ConEmu
  > Filezilla
    - Windows와 Server간의 파일 전송

bin/hdfs -dfs mkdir /input
bin/hadoop fs mkdir /input

 bin/hadoop jar share/hadoop/mapreduce/hadoop-mapreduce-examples-3.2.0.jar grep input/deep_learning.txt output/deep_learning '[a-z.]+'


 curl https://en.wikipedia.org/wiki/Deep_learning



 cat output/deep_learning/* > dl_word.txt

vi dl_word.txt
</pre>
