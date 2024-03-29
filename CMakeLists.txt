cmake_minimum_required(VERSION 3.5)
project(cppstdlib VERSION 1.0.0 LANGUAGES C CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

#FIND_LIBRARY(RUNTIME_LIB rt /usr/lib  /usr/local/lib NO_DEFAULT_PATH)

add_executable(accumulate1 algo/accumulate1.cpp)
add_executable(adjacentdiff1 algo/adjacentdiff1.cpp)
add_executable(adjacentfind1 algo/adjacentfind1.cpp)
add_executable(allanynone1 algo/allanynone1.cpp)
add_executable(binarysearch1 algo/binarysearch1.cpp)
add_executable(bounds1 algo/bounds1.cpp)
add_executable(copy1 algo/copy1.cpp)
add_executable(copy2 algo/copy2.cpp)
add_executable(copy3 algo/copy3.cpp)
add_executable(count1 algo/count1.cpp)
add_executable(equal1 algo/equal1.cpp)
add_executable(equalrange1 algo/equalrange1.cpp)
add_executable(fill1 algo/fill1.cpp)
add_executable(find1 algo/find1.cpp)
add_executable(find2 algo/find2.cpp)
add_executable(findend1 algo/findend1.cpp)
add_executable(findof1 algo/findof1.cpp)
add_executable(foreach1 algo/foreach1.cpp)
add_executable(foreach2 algo/foreach2.cpp)
add_executable(foreach3 algo/foreach3.cpp)
add_executable(generate1 algo/generate1.cpp)
add_executable(heap1 algo/heap1.cpp)
add_executable(includes1 algo/includes1.cpp)
add_executable(innerproduct1 algo/innerproduct1.cpp)
add_executable(inplacemerge1 algo/inplacemerge1.cpp)
add_executable(iota1 algo/iota1.cpp)
add_executable(isheap1 algo/isheap1.cpp)
add_executable(ispartitioned1 algo/ispartitioned1.cpp)
add_executable(ispermutation1 algo/ispermutation1.cpp)
add_executable(issorted1 algo/issorted1.cpp)
add_executable(lexicocmp1 algo/lexicocmp1.cpp)
add_executable(merge1 algo/merge1.cpp)
add_executable(minmax1 algo/minmax1.cpp)
add_executable(mismatch1 algo/mismatch1.cpp)
add_executable(move1 algo/move1.cpp)
add_executable(nthelement1 algo/nthelement1.cpp)
add_executable(partialsort1 algo/partialsort1.cpp)
add_executable(partialsort2 algo/partialsort2.cpp)
add_executable(partialsum1 algo/partialsum1.cpp)
add_executable(partition1 algo/partition1.cpp)
add_executable(partitioncopy1 algo/partitioncopy1.cpp)
add_executable(randomshuffle1 algo/randomshuffle1.cpp)
add_executable(relabs1 algo/relabs1.cpp)
add_executable(remove1 algo/remove1.cpp)
add_executable(remove2 algo/remove2.cpp)
add_executable(replace1 algo/replace1.cpp)
add_executable(replace2 algo/replace2.cpp)
add_executable(reverse1 algo/reverse1.cpp)
add_executable(rotate1 algo/rotate1.cpp)
add_executable(rotate2 algo/rotate2.cpp)
add_executable(search1 algo/search1.cpp)
add_executable(search2 algo/search2.cpp)
add_executable(searchn1 algo/searchn1.cpp)
add_executable(shuffle1 algo/shuffle1.cpp)
add_executable(sort1 algo/sort1.cpp)
add_executable(sort2 algo/sort2.cpp)
add_executable(sorted1 algo/sorted1.cpp)
add_executable(swapranges1 algo/swapranges1.cpp)
add_executable(transform1 algo/transform1.cpp)
add_executable(transform2 algo/transform2.cpp)
add_executable(unique1 algo/unique1.cpp)
add_executable(unique2 algo/unique2.cpp)
add_executable(unique3 algo/unique3.cpp)

#add_executable(myalloc03 alloc/myalloc03.cpp)
#add_executable(myalloc11 alloc/myalloc11.cpp)

#add_executable(async1 concurrency/async1.cpp)
#add_executable(async2 concurrency/async2.cpp)
#add_executable(async3 concurrency/async3.cpp)
#add_executable(atomics1 concurrency/atomics1.cpp)
#add_executable(condvar1 concurrency/condvar1.cpp)
#add_executable(condvar2 concurrency/condvar2.cpp)
#add_executable(mutex1 concurrency/mutex1.cpp)
#add_executable(promise1 concurrency/promise1.cpp)
#add_executable(sharedfuture1 concurrency/sharedfuture1.cpp)
#add_executable(thread1 concurrency/thread1.cpp)

#add_executable(array1 cont/array1.cpp)
#add_executable(cstylearray1 cont/cstylearray1.cpp)
#add_executable(cstylearray1old cont/cstylearray1old.cpp)
#add_executable(deque cont/deque1.cpp)
#add_executable(forwardlist1 cont/forwardlist1.cpp)
#add_executable(forwardlistfind1 cont/forwardlistfind1.cpp)
#add_executable(forwardlistsplice1 cont/forwardlistsplice1.cpp)
#add_executable(hashfunc1 cont/hashfunc1.cpp)
#add_executable(hashfunc2 cont/hashfunc2.cpp)
#add_executable(list1 cont/list1.cpp)
#add_executable(map1 cont/map1.cpp)
#add_executable(map2 cont/map2.cpp)
#add_executable(mapcmp1 cont/mapcmp1.cpp)
#add_executable(mapfind1 cont/mapfind1.cpp)
#add_executable(multimap1 cont/multimap1.cpp)
#add_executable(multiset1 cont/multiset1.cpp)
#add_executable(refsem1 cont/refsem1.cpp)
#add_executable(refwrap1 cont/refwrap1.cpp)
#add_executable(set1 cont/set1.cpp)
#add_executable(setcmp1 cont/setcmp1.cpp)
#add_executable(setrange1 cont/setrange1.cpp)
#add_executable(sortset cont/sortset.cpp)
#add_executable(sortvec cont/sortvec.cpp)
#add_executable(unordinspect1 cont/unordinspect1.cpp)
#add_executable(unordmultimap1 cont/unordmultimap1.cpp)
#add_executable(unordmultiset1 cont/unordmultiset1.cpp)
#add_executable(unordset1 cont/unordset1.cpp)
#add_executable(vector1 cont/vector1.cpp)

#add_executable(bitset1 contadapt/bitset1.cpp)
#add_executable(bitset2 contadapt/bitset2.cpp)
#add_executable(priorityqueue1 contadapt/priorityqueue1.cpp)
#add_executable(queue1 contadapt/queue1.cpp)
#add_executable(queue2 contadapt/queue2.cpp)
#add_executable(stack1 contadapt/stack1.cpp)
#add_executable(stack2 contadapt/stack2.cpp)

#add_executable(bind1 fo/bind1.cpp)
#add_executable(bind2 fo/bind2.cpp)
#add_executable(compose3 fo/compose3.cpp)
#add_executable(fopow1 fo/fopow1.cpp)
#add_executable(foreach3 fo/foreach3.cpp)
#add_executable(lambda2 fo/lambda2.cpp)
#add_executable(lambda3 fo/lambda3.cpp)
#add_executable(lambda4 fo/lambda4.cpp)
#add_executable(lambda5 fo/lambda5.cpp)
#add_executable(lambda6 fo/lambda6.cpp)
#add_executable(removeif1 fo/removeif1.cpp)
#add_executable(sequence1 fo/sequence1.cpp)
#add_executable(sequence2 fo/sequence2.cpp)
#add_executable(sort1 fo/sort1.cpp)

#add_executable(germanbool i18n/germanbool.cpp)
#add_executable(loc1 i18n/loc1.cpp)
#add_executable(loc2 i18n/loc2.cpp)
#add_executable(moneymanipulator i18n/moneymanipulator.cpp)
#add_executable(moneypunct i18n/moneypunct.cpp)
#add_executable(numget i18n/numget.cpp)
#add_executable(numput i18n/numput.cpp)
#add_executable(timeget i18n/timeget.cpp)
#add_executable(timeput i18n/timeput.cpp)
#add_executable(wbuffer i18n/wbuffer.cpp)
#add_executable(wstring2string i18n/wstring2string.cpp)
#add_executable(wstring2utf8 i18n/wstring2utf8.cpp)

#add_executable(cat1 io/cat1.cpp)
#add_executable(cat2 io/cat2.cpp)
#add_executable(charcat1 io/charcat1.cpp)
#add_executable(charcat2 io/charcat2.cpp)
#add_executable(copy1 io/copy1.cpp)
#add_executable(copy2 io/copy2.cpp)
#add_executable(countlines1 io/countlines1.cpp)
#add_executable(fstream1 io/fstream1.cpp)
#add_executable(fstream2 io/fstream2.cpp)
#add_executable(ignore1 io/ignore1.cpp)
#add_executable(ignore2 io/ignore2.cpp)
#add_executable(inbuf1 io/inbuf1.cpp)
#add_executable(io1 io/io1.cpp)
#add_executable(outbuf1 io/outbuf1.cpp)
#add_executable(outbuf1i18n io/outbuf1i18n.cpp)
#add_executable(outbuf2 io/outbuf2.cpp)
#add_executable(outbuf3 io/outbuf3.cpp)
#add_executable(sstream1 io/sstream1.cpp)
#add_executable(sstream2 io/sstream2.cpp)
#add_executable(streambuffer1 io/streambuffer1.cpp)
#add_executable(streambuffer2 io/streambuffer2.cpp)
#add_executable(streamreadwrite1 io/streamreadwrite1.cpp)
#add_executable(streamredirect1 io/streamredirect1.cpp)
#add_executable(sum1 io/sum1.cpp)
#add_executable(sum2 io/sum2.cpp)
#add_executable(timemanipulator1 io/timemanipulator1.cpp)

#add_executable(advance1 iter/advance1.cpp)
#add_executable(advance2 iter/advance2.cpp)
#add_executable(assoiter1 iter/assoiter1.cpp)
#add_executable(backinserter1 iter/backinserter1.cpp)
#add_executable(distance1 iter/distance1.cpp)
#add_executable(frontinserter1 iter/frontinserter1.cpp)
#add_executable(inserter1 iter/inserter1.cpp)
#add_executable(istreamiter1 iter/istreamiter1.cpp)
#add_executable(itercategory1 iter/itercategory1.cpp)
#add_executable(iterswap1 iter/iterswap1.cpp)
#add_executable(ostreamiter1 iter/ostreamiter1.cpp)
#add_executable(reviter1 iter/reviter1.cpp)
#add_executable(reviter2 iter/reviter2.cpp)
#add_executable(reviter3 iter/reviter3.cpp)
#add_executable(reviter4 iter/reviter4.cpp)

#add_executable(complex1 num/complex1.cpp)
#add_executable(complex2 num/complex2.cpp)
#add_executable(dist1 num/dist1.cpp)
#add_executable(gslice1 num/gslice1.cpp)
#add_executable(indirectarray1 num/indirectarray1.cpp)
#add_executable(maskarray1 num/maskarray1.cpp)
#add_executable(random1 num/random1.cpp)
#add_executable(random2 num/random2.cpp)
#add_executable(slice1 num/slice1.cpp)
#add_executable(valarray1 num/valarray1.cpp)
#add_executable(valarray2 num/valarray2.cpp)

#add_executable(regex1 regex/regex1.cpp)
#add_executable(regex2 regex/regex2.cpp)
#add_executable(regex3 regex/regex3.cpp)
#add_executable(regex4 regex/regex4.cpp)
#add_executable(regex5 regex/regex5.cpp)
#add_executable(regexiter1 regex/regexiter1.cpp)
#add_executable(regextokeniter1 regex/regextokeniter1.cpp)

#add_executable(lambda1 lang/lambda1.cpp)

#add_executable(add1 stl/add1.cpp)
#add_executable(algo1 stl/algo1.cpp)
#add_executable(algo1old stl/algo1old.cpp)
#add_executable(array1 stl/array1.cpp)
#add_executable(assoarray1 stl/assoarray1.cpp)
#add_executable(bind1 stl/bind1.cpp)
#add_executable(copy1 stl/copy1.cpp)
#add_executable(copy2 stl/copy2.cpp)
#add_executable(copybug stl/copybug.cpp)
#add_executable(deque1 stl/deque1.cpp)
#add_executable(find1 stl/find1.cpp)
#add_executable(foreach1 stl/foreach1.cpp)
#add_executable(foreach2 stl/foreach2.cpp)
#add_executable(forwardlist1 stl/forwardlist1.cpp)
#add_executable(ioiter1 stl/ioiter1.cpp)

#add_executable(string_icstring1 string/icstring1.cpp)
#add_executable(string_string1 string/string1.cpp)
#add_executable(string_string2 string/string2.cpp)
#add_executable(string_string3 string/string3.cpp)
#add_executable(stringiter1 string/stringiter1.cpp)
#add_executable(stringiter2 string/stringiter2.cpp)
#add_executable(stringnumconv1 string/stringnumconv1.cpp)

#add_executable(util_chrono1 util/chrono1.cpp)
#add_executable(util_chrono2 util/chrono2.cpp)
#add_executable(util_clock1 util/clock1.cpp)
#add_executable(util_enableshared1 util/enableshared1.cpp)
#add_executable(util_limits1 util/limits1.cpp)
#add_executable(util_minmax1 util/minmax1.cpp)
#add_executable(util_pair1 util/pair1.cpp)
#add_executable(util_ratio1 util/ratio1.cpp)
#add_executable(util_sharedptr1 util/sharedptr1.cpp)
#add_executable(util_sharedptr2 util/sharedptr2.cpp)
#add_executable(util_sharedptr3 util/sharedptr3.cpp)
#add_executable(util_timepoint1 util/timepoint1.cpp)
#add_executable(util_tuple1 util/tuple1.cpp)
#add_executable(util_tuple2 util/tuple2.cpp)
#add_executable(util_uniqueptr1 util/uniqueptr1.cpp)
#add_executable(util_weakptr1 util/weakptr1.cpp)
#add_executable(util_weakptr2 util/weakptr2.cpp)

#target_link_libraries(util_sharedptr3 rt)

#target_link_libraries(util_sharedptr3 libshared.a libboost_thread.a libboost_chrono.a libboost_system.a pthread dl rt)

