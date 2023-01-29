# 6. Git: Branch & Merge

~~~
Branch adalah cabang yang digunakan untuk membuat snapshot
tanpa mengganggu jalur utamanya.
Branch berguna untuk fitur experimental, 2 orang menggunakan
repository yang sama.

Merging adalah proses menyatukan branch menjadi satu kesatuan utuh.
~~~
~~~
Dalam video ini diajarkan bagaimana cara melakukan
branching dan merging file pada Git.
Branching pada Git tidak sesederhana melakukan branching
pada GitHub, ada branch yang mengarah ke commit.
Satu commit bisa terdiri dari beberapa branch.
Untuk mengetahui kita ada di branch mana, ada yang bernama "Head".
~~~
~~~
Untuk pindah dari satu branch ke branch lain,
gunakan $ git checkout <nama branch>.
~~~
~~~
Jenis Merge dalam Git
- Fast Forward
    terjadi ketika branch berada dalam jalur langsung (direct path).
- Three-way  Merge
    terjadi ketika branch berada di dalam direct path yang berbeda.
~~~
~~~
Untuk menghapus branch gunakan
$ git branch -d <nama branch>
~~~