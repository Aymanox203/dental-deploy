<script>
    import FurcationTable from "../../components/FurcationTable.svelte";
    import NestedTeethTable from "../../components/NestedTeethTable.svelte";
    import TeethTable from "../../components/TeethTable.svelte";


</script>

    <div class="flex justify-center">
        <div class="w-4/5 bg-gray-300 h-auto flex-col rounded-xl max-w-5xl min-w-[650px]">
            <div class="flex flex-col items-center p-16">
                <h1 class="text-3xl font-bold p-4">Parodontologie service</h1>
                <p class="text-xl">Parodentic diagnosis file</p>
            </div>
            <hr class="border-t-2">
            <div class="p-5">
                <h2 class="text-2xl py-3">Patient info:</h2>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">First name:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Last name:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">age name:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Adress:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Phone number:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Supporting student:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <h2 class="text-2xl py-3">Interview:</h2>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Consultation motif:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">General anamnesis:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">General pathology:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">On going medication:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Smoking:</span>

                        <div class="basis-3/4 flex flex-wrap">
                            <div class="flex  flex-wrap mr-2">
                                <span class="mr-1">Yes</span>
                                <input type="radio" class="mx-1">
                            </div>
                            <div class="flex flex-wrap mx-4">
                                <span class="mr-2">No</span>
                                <input type="radio" class="mx-1">
                            </div>
                            <div class="flex flex-wrap mx-4">
                                <span class="mr-2">Cig per day</span>
                                <input type="text" class="border-2 border-gray-500 rounded-md px-2 mx-1 max-w-20 ">
                            </div>
                            <div class="flex flex-wrap mx-4">
                                <span class="mr-2">Duration:</span>
                                <input type="text" class="border-2 border-gray-500 rounded-md px-2 mx-1 max-w-20">
                            </div>
                        </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Other:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Local anamnesis:</span>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Dental hygene:</span>
                        <div class="basis-3/4 flex flex-wrap">
                            <div class="flex flex-wrap mr-4">
                                <span class="mr-2">Frequency:</span>
                                <input type="text" class="border-2 border-gray-500 rounded-md px-2 mx-1 max-w-20 ">
                            </div>
                            <div class="flex flex-wrap mx-4">
                                <span class="mr-2">Tool:</span>
                                <input type="text" class="border-2 border-gray-500 rounded-md px-2 mx-1 max-w-24">
                            </div>
                        </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Chewing type:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Timeline of periodontal disease:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Previous treatment:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Latest visit date:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <h2 class="text-2xl py-3">Exobuccal exam:</h2>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Facial symmetry:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Swelling:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Adenopathy:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Stomion:</span>

                        <div class="basis-3/4 flex flex-wrap">
                            <div class="flex  flex-wrap mr-2">
                                <span class="mr-1">Yes</span>
                                <input type="radio" class="mx-1">
                            </div>
                            <div class="flex flex-wrap mx-4">
                                <span class="mr-2">No</span>
                                <input type="radio" class="mx-1">
                            </div>
                        </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Tics and habits:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <h2 class="text-2xl py-3">Endobuccal exam:</h2>
                <h2 class="text-xl py-3 px-2">plaque index, SILNESS & LOE</h2>
                <div class="grid grid-cols-2">
                    <div class="flex flex-col">
                        <span class="text-md px-4 font-semibold">0 = No plaque</span>
                        <span class="text-md px-4 font-semibold">1 = Thin plaque band</span>
                        <span class="text-md px-4 font-semibold">2 = Moderate Plaque accumulation</span>
                        <span class="text-md px-4 font-semibold">3 = Big Plaque accumulation</span>
                    </div>
                    <div class="grid grid-cols-2 grid-rows-2">
                        <div class="p-2 border-r-[1px] border-b-[1px] border-black flex justify-between">
                            <span class="absolute z-0 translate-x-1 -translate-y-3 text-xs text-gray-500">1</span>
                            <span class="absolute z-0 translate-x-5 translate-y-1 text-xs text-gray-500">2</span>
                            <span class="absolute z-0 translate-x-1.5 translate-y-[15px] text-xs text-gray-500">3</span>
                            <span class="absolute z-0 -translate-x-2 translate-y-1 text-xs text-gray-500">4</span>
                            <span>16</span>
                            <span>22</span>
                        </div>
                        <div class="p-2 border-l-[1px] border-b-[1px] border-black text-center">23</div>
                        <div class="p-2 border-r-[1px] border-t-[1px] border-black text-center">44</div>
                        <div class="p-2 border-l-[1px] border-t-[1px] border-black flex justify-between "><span>32</span><span>36</span></div>
                    </div>
                </div>
                <span class="text-gray-600 text-sm ml-3">*Fill out the four Indexes Top-right-bottom-left recpectively e.g. 0101 </span>
                <div class="flex py-2">
                    <span class="text-md px-4 font-semibold">Indeces:</span>

                        <div class="flex flex-wrap">
                            <div class="flex flex-wrap mx-2">
                                <span class="mr-2">16</span>
                                <input type="text" placeholder="1234" class="border-2 border-gray-500 rounded-md px-2 mx-1 max-w-20 ">
                            </div>
                            <div class="flex flex-wrap mx-2">
                                <span class="mr-2">22:</span>
                                <input type="text" placeholder="1234" class="border-2 border-gray-500 rounded-md px-2 mx-1 max-w-20">
                            </div>
                            <div class="flex flex-wrap mx-2">
                                <span class="mr-2">23</span>
                                <input type="text" placeholder="1234" class="border-2 border-gray-500 rounded-md px-2 mx-1 max-w-20 ">
                            </div>
                            <div class="flex flex-wrap mx-2">
                                <span class="mr-2">44:</span>
                                <input type="text" placeholder="1234" class="border-2 border-gray-500 rounded-md px-2 mx-1 max-w-20">
                            </div>
                            <div class="flex flex-wrap mx-2">
                                <span class="mr-2">32</span>
                                <input type="text" placeholder="1234" class="border-2 border-gray-500 rounded-md px-2 mx-1 max-w-20 ">
                            </div>
                            <div class="flex flex-wrap mx-2">
                                <span class="mr-2">36:</span>
                                <input type="text" placeholder="1234" class="border-2 border-gray-500 rounded-md px-2 mx-1 max-w-20">
                            </div>
                        </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">I=Total/24=</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <h2 class="text-xl py-3 px-2">Oral environment</h2>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Tongue:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Palate:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Cheeks:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">floor:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <h2 class="text-xl py-3 px-2">Dental Exam</h2>
                <p class="text-md px-4">C = Has carries(Cp=proximal, Co = Occlusal, Cc = Cervical)</p>
                <p class="text-md px-4">A = Absent (Ap= Absent periodontitis, Ac = Carries absent)</p>
                <p class="text-md px-4">Filling</p>

                <TeethTable />
                
                <h2 class="text-xl py-3 px-2">Periodontal exam</h2>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Gum caracteristiques:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>

                <h2 class="text-xl py-3 px-2">Gingival index, SILNESS & LOE</h2>
                <div class="grid grid-cols-2">
                    <div class="flex flex-col">
                        <span class="text-md px-4 font-semibold">0 = No inflamation</span>
                        <span class="text-md px-4 font-semibold">1 = Coloring</span>
                        <span class="text-md px-4 font-semibold">2 = bleeding tendency on probing </span>
                        <span class="text-md px-4 font-semibold">3 = Big inflamation and spontanious bleeding</span>
                    </div>
                    <div class="grid grid-cols-2 grid-rows-2">
                        <div class="p-2 border-r-[1px] border-b-[1px] border-black flex justify-between">
                            <span class="absolute z-0 translate-x-1 -translate-y-3 text-xs text-gray-500">1</span>
                            <span class="absolute z-0 translate-x-5 translate-y-1 text-xs text-gray-500">2</span>
                            <span class="absolute z-0 translate-x-1.5 translate-y-[15px] text-xs text-gray-500">3</span>
                            <span class="absolute z-0 -translate-x-2 translate-y-1 text-xs text-gray-500">4</span>
                            <span>16</span>
                            <span>22</span>
                        </div>
                        <div class="p-2 border-l-[1px] border-b-[1px] border-black text-center">23</div>
                        <div class="p-2 border-r-[1px] border-t-[1px] border-black text-center">44</div>
                        <div class="p-2 border-l-[1px] border-t-[1px] border-black flex justify-between "><span>32</span><span>36</span></div>
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">I=Total/24=</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <h2 class="text-xl py-3 px-2">Gum recession and keratinized gingiva</h2>
                <NestedTeethTable />

                <h2 class="text-xl py-3 px-2">Pocket depth(* = bleed on probing)</h2>
                <NestedTeethTable />

                <h2 class="text-xl py-3 px-2">Mobility: Mühlemann index</h2>
                <p class="text-sm">0=Ankylosis; 1=Physical mobility; 2=Transversal mobility &lt;1mm;</p>
                <p class="text-sm">3=Transversal mobility &gt;1mm; 4=Axial mobility</p>
                <TeethTable />

                <h2 class="text-xl py-3 px-2">Furcation involvement: HAMP & al.(1975)</h2>
                <p class="text-sm">CL Ⅰ=Horizontal bone loss &lt;3mm; CL Ⅱ=Horizontal bone loss&gt;3mm</p>
                <p class="text-sm">CL Ⅲ=Through and through horizontal lesion</p>
                <FurcationTable />

                <h2 class="text-xl py-3 px-2">Occlusal examination</h2>
                <span class="text-md px-4 font-semibold">Static examination:</span>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Over bite:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Over jet:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Angle class:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <span class="text-md px-4 font-semibold">Dynamic examination:</span>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">Function:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <span class="text-md px-4 font-semibold">Interference:</span>
                <div class="ml-5">
                    <div class="flex py-2 justify-between">
                        <span class="text-md px-4 font-semibold">Right deviation:</span>
                        <div class="basis-3/4">
                            <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                        </div>
                    </div>
                    <div class="flex py-2 justify-between">
                        <span class="text-md px-4 font-semibold">Left deviation:</span>
                        <div class="basis-3/4">
                            <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                        </div>
                    </div>
                    <div class="flex py-2 justify-between">
                        <span class="text-md px-4 font-semibold">Propulsion:</span>
                        <div class="basis-3/4">
                            <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                        </div>
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <span class="text-md px-4 font-semibold">TMJ examination:</span>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <h2 class="text-xl">Radiology examination:</h2>
                    <div class="basis-3/4">
                        <input type="text" class="border-2 border-gray-500 rounded-md px-2 w-1/2">
                    </div>
                </div>
                <div class="flex py-2 justify-between">
                    <h2 class="text-xl py-3 px-2">Diagnostic:</h2>
                    <div class="basis-3/4">
                        <textarea name="diagnostic" id="diagnostic" class="min-w-[400px] border border-black rounded min-h-20"></textarea>
                    </div>
                </div>







            </div>

        </div>
    </div>
    