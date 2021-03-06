add_library(engine STATIC
  # CMakeLists.txt
  Eschreyer.cpp
  Eschreyer.hpp
  GF.cpp
  GF.hpp
  LLL.cpp
  LLL.hpp
  # Makefile.common.in
  # Makefile.files
  # Makefile.in
  NAG.cpp
  NAG.hpp
  # README
  SLP-defs.hpp
  SLP-imp.hpp
  SLP.cpp
  SLP.hpp
  # STYLE.txt
  # TAGS
  # TODO
  # TODO-SLPs
  # TODO-numerics
  # TODO-reallocate-heap
  # TODO-rings-matrices
  ZZ.cpp
  ZZ.hpp
  ZZp.cpp
  ZZp.hpp
  aring-CC.cpp
  aring-CC.hpp
  aring-CCC.cpp
  aring-CCC.hpp
  aring-RR.cpp
  aring-RR.hpp
  aring-RRR.cpp
  aring-RRR.hpp
  aring-gf-flint-big.cpp
  aring-gf-flint-big.hpp
  aring-gf-flint.cpp
  aring-gf-flint.hpp
  aring-gf-givaro.cpp
  aring-gf-givaro.hpp
  aring-glue.hpp
  aring-m2-gf.cpp
  aring-m2-gf.hpp
  aring-qq-flint.cpp
  aring-qq-flint.hpp
  aring-qq-gmp.cpp
  aring-qq-gmp.hpp
  aring-qq.hpp
  aring-tower.cpp
  aring-tower.hpp
  aring-translate.hpp
  # aring-wrap.cpp
  # aring-wrap.hpp
  aring-zz-flint.cpp
  aring-zz-flint.hpp
  aring-zz-gmp.cpp
  aring-zz-gmp.hpp
  aring-zzp-ffpack.cpp
  aring-zzp-ffpack.hpp
  aring-zzp-flint.cpp
  aring-zzp-flint.hpp
  aring-zzp.cpp
  aring-zzp.hpp
  # aring.cpp
  aring.hpp
  array.hpp
  assprime.cpp
  assprime.hpp
  betti.cpp
  betti.hpp
  buffer.cpp
  buffer.hpp
  coeffrings.cpp
  coeffrings.hpp
  comb.cpp
  comb.hpp
  comp-gb-declared.cpp
  comp-gb-declared.hpp
  comp-gb-proxy.cpp
  comp-gb-proxy.hpp
  comp-gb.cpp
  comp-gb.hpp
  comp-res.cpp
  comp-res.hpp
  comp.cpp
  comp.hpp
  complex.c
  complex.h
  cra.cpp
  cra.hpp
  debug.cpp
  debug.hpp
  defgroups.h
  det.cpp
  det.hpp
  # dmat-ffpack.cpp
  dmat-gf-flint-big.hpp
  dmat-gf-flint.hpp
  dmat-lu-inplace.hpp
  dmat-lu-qq.hpp
  dmat-lu-zzp-ffpack.hpp
  dmat-lu-zzp-flint.hpp
  dmat-lu.hpp
  dmat-qq-flint.hpp
  dmat-qq-interface-flint.hpp
  dmat-zz-flint.hpp
  dmat-zzp-flint.hpp
  dmat.cpp
  dmat.hpp
  # doxygen-main.hpp
  # doxygen-settings
  # doxygen.conf
  dpoly.cpp
  dpoly.hpp
  engine-includes.hpp
  engine.cpp
  engine.h
  error.c
  error.h
  exceptions.hpp
  exptable.c
  exptable.h
  # f4
  # factor.cpp
  finalize.cpp
  finalize.hpp
  fplll-interface.cpp
  fplll-interface.hpp
  frac.cpp
  frac.hpp
  fractionfreeLU.cpp
  fractionfreeLU.hpp
  # franzi-brp-test.cpp
  franzi-brp.cpp
  franzi-brp.hpp
  franzi-gb.cpp
  franzi-interface.cpp
  freemod.cpp
  freemod.hpp
  gauss.cpp
  gauss.hpp
  gb-default.cpp
  gb-default.hpp
  gb-homog2.cpp
  gb-homog2.hpp
  gb-sugarless.cpp
  gb-sugarless.hpp
  gb-test1.cpp
  gb-test1.hpp
  gb-toric.cpp
  gb-toric.hpp
  gb-trace.hpp
  gb-walk.cpp
  gb-walk.hpp
  gbring.cpp
  gbring.hpp
  gbweight.cpp
  gbweight.hpp
  geopoly.hpp
  geovec.hpp
  hash.hpp
  hermite.cpp
  hermite.hpp
  hilb.cpp
  hilb.hpp
  imonorder.cpp
  imonorder.hpp
  index.hpp
  # int-bag.cpp
  int-bag.hpp
  intarray.cpp
  intarray.hpp
  interreduce.cpp
  interreduce.hpp
  interrupted.cpp
  interrupted.hpp
  lapack.cpp
  lapack.hpp
  localring.cpp
  localring.hpp
  mat-arith.hpp
  mat-elem-ops.hpp
  mat-linalg.hpp
  mat-util.hpp
  mat.cpp
  mat.hpp
  matrix-con.cpp
  matrix-con.hpp
  matrix-kbasis.cpp
  matrix-sort.cpp
  matrix-stream.cpp
  matrix-stream.hpp
  matrix-symm.cpp
  matrix.cpp
  matrix.hpp
  mem.cpp
  mem.hpp
  memory-status.cpp
  memory-status.hpp
  monideal-minprimes.cpp
  monideal-minprimes.hpp
  monideal.cpp
  monideal.hpp
  monoid.cpp
  monoid.hpp
  # monomial-sets.cpp
  monomial-sets.hpp
  monomial.cpp
  monomial.hpp
  monordering.c
  monordering.h
  montable.cpp
  montable.hpp
  montableZZ.cpp
  montableZZ.hpp
  mutablecomplex.cpp
  mutablecomplex.hpp
  mutablemat-defs.hpp
  mutablemat-imp.hpp
  # mutablemat.cpp
  mutablemat.hpp
  newdelete.cpp
  newdelete.hpp
  ntl-debugio.cpp
  ntl-interface.cpp
  ntl-interface.hpp
  ntl-internal.cpp
  ntuple.cpp
  ntuple.hpp
  # overflow-test.cpp
  overflow.cpp
  overflow.hpp
  pfaff.cpp
  pfaff.hpp
  # points.cpp
  # points.hpp
  poly.cpp
  poly.hpp
  polyquotient.cpp
  polyquotient.hpp
  polyring.cpp
  polyring.hpp
  polyroots.cpp
  polyroots.hpp
  qring.cpp
  qring.hpp
  queue.hpp
  rand.c
  rand.h
  reader.cpp
  reader.hpp
  reducedgb-ZZ.cpp
  reducedgb-ZZ.hpp
  reducedgb-field-local.cpp
  reducedgb-field-local.hpp
  reducedgb-field.cpp
  reducedgb-field.hpp
  reducedgb-marked.cpp
  reducedgb-marked.hpp
  reducedgb.cpp
  reducedgb.hpp
  relem.cpp
  relem.hpp
  res-a0-pair.hpp
  res-a0-poly.cpp
  res-a0-poly.hpp
  res-a0.cpp
  res-a0.hpp
  res-a1-poly.cpp
  res-a1-poly.hpp
  res-a1.cpp
  res-a1.hpp
  res-a2-gb.cpp
  res-a2.cpp
  res-a2.hpp
  ring-vecs.cpp
  ring.cpp
  ring.hpp
  ringelem.hpp
  ringmap.cpp
  ringmap.hpp
  sagbi.cpp
  sagbi.hpp
  schorder.cpp
  schorder.hpp
  schur-poly-heap.hpp
  schur.cpp
  schur.hpp
  schur2.cpp
  schur2.hpp
  schurSn.cpp
  schurSn.hpp
  skew.cpp
  skew.hpp
  skewpoly.cpp
  skewpoly.hpp
  smat.hpp
  solvable.cpp
  solvable.hpp
  spair.cpp
  spair.hpp
  stdinc-m2.hpp
  stop.hpp
  style.hpp
  table.c
  table.h
  test.dd
  text-io.cpp
  text-io.hpp
  timing.hpp
  tower.cpp
  tower.hpp
  unit-tests
  util.cpp
  util.hpp
  varpower.cpp
  varpower.hpp
  weylalg.cpp
  weylalg.hpp
  x-aring.cpp
  x-factor.cpp
  x-factor.hpp
  x-free.cpp
  x-gb.cpp
  x-mat.cpp
  x-monideal.cpp
  x-monoid.cpp
  # x-monom.cpp
  x-mutablemat.cpp
  x-relem.cpp
  x-ringmap.cpp
  f4/f4-computation.cpp
  f4/f4-computation.hpp
  f4/f4-m2-interface.cpp
  f4/f4-m2-interface.hpp
  f4/f4-mem.cpp
  f4/f4-mem.hpp
  f4/f4-monlookup.cpp
  f4/f4-monlookup.hpp
  f4/f4-spairs.cpp
  f4/f4-spairs.hpp
  f4/f4-syz.cpp
  f4/f4-syz.hpp
  # f4/f4-types.cpp
  f4/f4-types.hpp
  f4/f4.cpp
  f4/f4.hpp
  f4/gausser.cpp
  f4/gausser.hpp
  f4/hilb-fcn.cpp
  f4/hilb-fcn.hpp
  # f4/memblock.cpp
  f4/memblock.hpp
  f4/monhashtable.cpp
  f4/monhashtable.hpp
  f4/moninfo.cpp
  f4/moninfo.hpp
  f4/moninfo2.hpp
  f4/monsort.cpp
  f4/monsort.hpp
  f4/ntuple-monomial.cpp
  f4/ntuple-monomial.hpp
  f4/res-f4-computation.cpp
  f4/res-f4-computation.hpp
  f4/res-f4-m2-interface.cpp
  f4/res-f4-m2-interface.hpp
  f4/res-f4-monlookup.cpp
  f4/res-f4-monlookup.hpp
  f4/res-f4.cpp
  f4/res-f4.hpp
  f4/res-gausser-QQ-hybrid.cpp
  f4/res-gausser-QQ-hybrid.hpp
  f4/res-gausser-QQ.cpp
  f4/res-gausser-QQ.hpp
  f4/res-gausser-ZZp.cpp
  f4/res-gausser-ZZp.hpp
  f4/res-gausser.cpp
  f4/res-gausser.hpp
  f4/res-memblock.hpp
  f4/res-moninfo-dense.cpp
  f4/res-moninfo-dense.hpp
  f4/res-moninfo-sparse.cpp
  f4/res-moninfo-sparse.hpp
  # f4/res-moninfo.cpp
  f4/res-moninfo.hpp
  f4/res-monomial-sorter.cpp
  f4/res-monomial-sorter.hpp
  f4/res-monomial-types.hpp
  f4/res-poly-ring.cpp
  f4/res-poly-ring.hpp
  f4/res-schreyer-frame.cpp
  f4/res-schreyer-frame.hpp
  f4/res-schreyer-order.hpp
  f4/res-varpower-monomial.cpp
  f4/res-varpower-monomial.hpp
  f4/varpower-monomial.cpp
  f4/varpower-monomial.hpp  
  )

#  aring-wrap.cpp
#  aring-wrap.hpp
#  doxygen-settings
#  fixspace
#  franzi-brp-test.cpp
#  monorder.cpp
#  monorder.hpp
#  overflow-test.cpp
#  pi-genmask.cc
#  pi-readme.txt
#  pi-test.cc
#  pi.cc
#  pi.h
#  pm-test.cpp
#  pm.cpp
#  pm.hpp
#  points.cpp
#  points.hpp
#  f4/Makefile.files
#  f4/Makefile.in
#  f4/README-RES-F4

  set(UNITTESTS
  unit-tests/ARingCCCTest.cpp
  unit-tests/ARingCCTest.cpp
  unit-tests/ARingGFTest.cpp
  unit-tests/ARingQQFlintTest.cpp
  unit-tests/ARingQQGmpTest.cpp
  unit-tests/ARingRRRTest.cpp
  unit-tests/ARingRRTest.cpp
  unit-tests/ARingTest.hpp
  unit-tests/ARingZZTest.cpp
  unit-tests/ARingZZpTest.cpp
  unit-tests/DMatTest.hpp
  unit-tests/DMatZZpTest.cpp
  unit-tests/GivaroTest.cpp
  unit-tests/M2-cpp-replacement.cpp
  unit-tests/M2-replacement.c
  unit-tests/M2mem-replacement.c
  unit-tests/M2mem-replacement.h
  unit-tests/Makefile.files
  unit-tests/Makefile.in
  unit-tests/PointArray.cpp
  unit-tests/README
  unit-tests/ResTest.cpp
  unit-tests/RingCCCTest.cpp
  unit-tests/RingQQTest.cpp
  unit-tests/RingRRRTest.cpp
  unit-tests/RingTest.hpp
  unit-tests/RingTowerTest.cpp
  unit-tests/RingZZTest.cpp
  unit-tests/RingZZpTest.cpp
  unit-tests/SubsetTest.cpp
  unit-tests/basics-test.cpp
  unit-tests/fromStream.cpp
  unit-tests/gtest-include.cpp
  unit-tests/testMain.cpp
  )

target_include_directories(engine PUBLIC
  ${BOOTSTRAP}/include
  ${BOOTSTRAP}/Macaulay2/d
  ${BOOTSTRAP}/Macaulay2/e-includes
  ${BOOTSTRAP}/usr-host/include
  ../../submodules/memtailor/src
  ../../submodules/mathic/src
  ../../submodules/mathicgb/src
  ../../include
  .
  ../c
  )                            

#target_link_libraries(engine STATIC )
